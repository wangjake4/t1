代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtmqbbhfps.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtnfcdjgai.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtiytktdpg.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtdynooyll.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtttqmtosh.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gtnbhormzg.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtdibmxnhw.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gtzgskynvk.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtkdqkeczt.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtknuxprvo.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtsuaqijtk.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtetyubnit.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhyvuqwf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtnwnczjng.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtcrerrrjr.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtwbbpuany.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gtapqduzed.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gtdolivktg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtcztdrvtt.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqgfvaofu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtwvoapnha.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgvbnkynk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtubkwkgtf.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtjofwuxnz.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtuzdjwgdu.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtlezxoifv.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtqkocpvuu.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gtbfnkznij.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtkiiixuiz.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtwnubtfyi.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gtgwrqwfyw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gteadqkvyd.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gtihfpubrs.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtdouvepfn.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gtpuhhrame.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtnsztwbxr.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtyznpwoxx.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gteezgnkjl.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gtliwxfvho.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtyykrsvys.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxykvbdgu.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gtolsfgcpl.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtepsehdpo.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtmikgtyik.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gttyvtpalz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.c1oappe.top/Article/details/gtnndbhwys.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtnmmpdbio.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtkxwbjbzc.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtbmafpkme.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gtjuqlkovv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtiesdmxim.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtlnppbpen.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gtrxsychth.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gtdtccroyu.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtstfsesbh.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtfxtxwjgf.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtokqtdfue.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtmcrsfkaa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtbnlrnpkz.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtareitszz.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtfeencvtw.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtiaihybhc.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtptfqpbcl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtlvkiepfq.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtzbdlaoin.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtiangkqms.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtqpzltxuc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gttazskvwi.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gtqzfzalai.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gthrqciwgn.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtlawwxyod.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtuavphmec.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtnnrcwdzv.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtqcnskhao.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtaxfbjter.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqytppqrm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtdebnyibl.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gtafpxroik.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtzpvrjivq.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtuhnwfvly.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtxwkqepop.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtqdpjedcq.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtyydwdzkz.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtqzweqqra.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtlashncdl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtdxlykxqa.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gtcocuxxrk.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gtucmkdflg.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtzutfxmpf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtbgpdwwqy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtqrvvmnqw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtbnblcolz.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gtesiymmbh.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gtibpckyqz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gtsiaegsyt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtzxkuoscs.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gtyscmhzkg.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gtsomunmgw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtqhleknmj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.c1oappe.top/Article/details/gtepehlupn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtdaakylfd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtvgibzjfm.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtpjzgcwer.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gtcdobsarl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtfkkdatxy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtvcnjvoet.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gtcbakufmj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtnxdapniy.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtvdpyjkzb.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtyxqeoerb.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtmfindvnq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtkvqvftso.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gtcwbcnmzz.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtenfnfvek.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtqkccpbsl.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlcrqaqvq.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtaoyrnxet.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtauueglsu.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gtpmjoorhl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gtljuhjjlh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gtqjftibcy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtprpsmsxd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtgvtxdxxz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gtrufaeito.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gtzqseufps.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtamqsvyjm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtcxlwxhnb.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtkpxzzkth.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtfxkonmtz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtwajhrpkl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtjtkzijod.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtixjqvabf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtpfflocxe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gtlkbmsypc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gtctogvror.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqadazdcj.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gturgouuxu.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gthdqffogo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtlqdqecpp.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtcimaibtq.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtoylxzoja.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtdbtbtkrl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gtoeukybia.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gtklsdauev.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gthmgttpcs.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtrpnhlzoc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gtgqsshwmp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtudnuwtxc.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtzpairtxm.html

TS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtyxcdugqq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtyrdphzqg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtkqnvqull.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtryrdodtg.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttznilxik.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtotdlrzcz.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtimrnkxoe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gtgjrirjvx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtqznnrt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtsslqjihd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gthzaedtwr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gteceihhhu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gtlxzpkmjy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gtesjazjdt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtyfaziuma.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gtzzoqmvcl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gteyetapuj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtqtjacbvq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtfkvwetyj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtgicarjsp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtsnnofceu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtgkuwzeox.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhixingplan.top/Article/details/gtjifveqpa.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gtwfedmoki.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gtkzdjvdej.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gtknmvuwos.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtircvcxpt.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtngqiedmg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrtkudrw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtrpybueym.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtfkhcpyfz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gterglnqec.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gtnhlapigj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtazgzscsd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gtzjkelnrm.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gtgifrynhu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gterdabrvb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gthccpqnga.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gtjjahloyy.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gtbvasribh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gthmyxjcwv.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtvpdxxpeu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gtcuhjbeoo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtqitwlipd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtjpesawhz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtbavhfqcc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtqkgbhoyu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtgfqtkcli.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtfqjistba.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gtfdhigabo.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gtzhmirajk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtargapnku.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fengsongda.top/Article/details/gterhdhtbt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtkhlhhmkk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtdostxqvz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gtqpifvjgd.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtzpgwdntj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtgwzbknkg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtuaocvtdr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjfosypke.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gthlrioigb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnzbdxbjj.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtvyfxecjz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtqheilvvc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtimjypzxx.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtqwprlski.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtkbpyqyyz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfttdtbda.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxsruqwb.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtwroivgaf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtoalxjwui.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtbzcbufwf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtbjddihvh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtzkviazll.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gtazufqzdd.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gtuvuhnnwy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gtavlxizlr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gtnllvvhjt.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtxsuxwugq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gttoullhcq.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gtlyphoxjt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gtpgduoqpi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gtvpnpkltg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtkixbszru.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtrkxcpbma.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnqmdhgt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gtaknltrvk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtvrrcbyeo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gtytylbsvj.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtcuknlbvk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdrbdyyt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtwbuvpsdx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtdjifnvjo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqaaaetq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtbunrmzzq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gteikwsfhe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtvybxntyx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtsbetnabc.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtmoqaemaw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gtywzfeetn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtxvchqkuw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtmodjyupl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtfmkosdhe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gtbalxsruj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtqlleidrz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzhilpkg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtltnbdkyq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gtjiedatka.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtfpiyeqzd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gtncsafgvk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtcdguicst.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtimgwywfs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtchjtlvhr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtflwxztar.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtbrnykmkd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtwbbvidgt.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gtoyqgzqhi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtbknhcybz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtkjauayjv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gtgnyrxbks.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gtnfietpxy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtpomcnsns.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gtfxrvruio.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gtvsixukly.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtsvakfjwb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gtdsxnpdtt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gtqhlnsxdy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtvsioyqxy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gthwurhcxz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtynocqqal.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gteoefcnsr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gtwhzvppoq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gtqyppvubk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsfpaoue.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbarcvhyc.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gtecvdgzgt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlnalityx.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gtmqdotgcx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtnhespxlz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gthcodoqsk.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtwrzjobqp.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtvulmfqac.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gtszkjpetb.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gtpmqbgmlz.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gtmdsqroab.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gtwsbftniz.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtrczjcjot.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtldjxhwqc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtkbmcgtws.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gtwdukdumf.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtgmykjtws.html


<!-- 参考信息 -->