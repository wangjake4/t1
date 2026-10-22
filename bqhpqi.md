代发 wailian999

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gt2manxduxj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gt2qmkshssd.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gt2xkpqgtsg.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gt2cjltqitz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2cdbrzxwh.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2byxasdxk.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2mfvkatas.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2pqajkfgs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2asibmvzu.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2umxsmowr.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gt2hdqtrles.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2givntcic.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gt2istbdemf.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2qpatqufy.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2pyufgebv.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ekdpoucp.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgryipsn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gt2obkeaheu.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjmavoza.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gt2lpjqdmge.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gt2rkepqscc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gt2ysydexyp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2hylpztcv.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2kdpwzcvs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wsxaokao.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2dlojfsot.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfmrawme.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itrcefoo.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gt2gpqdmrdu.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gt2ohourexx.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gt2dbvllzzn.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2jpluppon.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2wocrwvlt.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2yomislvz.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2tqgrmuhi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gt2ztqhfuxo.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gt2kaesppbg.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gt2twdzxuye.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjosgols.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gt2vnpljprh.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2kkudtssa.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2hxvqcwvo.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gt2xhtsrfsm.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2artosacm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gt2skjpmofj.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gt2ttqwpdrr.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2njellntv.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gt2skfwkxne.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bozzrqiv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnnwffcg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gt2veqxzhgf.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gt2imasvcnt.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2dtmynqja.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gt2iliwrkcp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gt2oamvubht.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2tqgmgaxl.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gt2kuvznzya.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gt2wnlutcmp.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2rvlmdepo.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gt2tbagxauv.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2ainmkmvn.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gt2xudkhagn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpqgeuyr.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2mviyvchv.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxpufcvw.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gt2rnhbhhnx.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2qjdkqhve.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfgnzwif.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2cffqpcck.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktwcycyo.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2tgnhvfxk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2lnxeuqgj.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gt2rkbmomqc.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gt2urheowre.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gt2bhkhkole.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gt2ahvwewao.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sioegjjz.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2vhnunwat.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2skuyieia.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2xxtvhszr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2yoetxodm.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmldtmmu.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2slwapuij.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gt2remgduke.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gt2qewplxdy.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2ihqezqqg.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2pwrgyjko.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2ivrvfkvl.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2mrjdzsgm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gt2ukvemxjd.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gt2ddafvzyo.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gt2xuaafkgb.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gt2rvwlnxls.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gt2vhggurys.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gt2bocgfhvc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gt2bitdulgb.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gt2kkpouolc.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udlkgesn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gt2lmcgppyz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gt2mlttzklo.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gt2ybhicrsm.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gt2vhofbtlj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kignevvt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gt2dlmlqevi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gt2kwvhmgoc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gt2gypodvue.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqlvjvej.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gt2mvnlmcpy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gt2vafwhhjk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2ciqhilxr.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gt2sdfnecum.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gt2iykocciy.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gt2awtuibrg.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2coelzvuf.html

TS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2lprxybkp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gt2nphicoyq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gt2inqcvpyb.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gt2rylqvbuz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uemgsarz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ysbfpcdf.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gt2atxlwfim.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtqsvpqo.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gt2ucefvplo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gt2qzfbodnn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gt2hjhzkzxt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2ioxdhrgq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2gznmywsp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2abebmblm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gt2fwsjusym.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gt2pqisvxqw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gt2swjxdeor.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gt2llkpcmqw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gt2yufquhfh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2tknysxqw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tehqxurz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2trkidvxl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2dxiaznuo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gt2fglhudad.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gt2gijgozoj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2yzsxyjrj.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2dcjvczsv.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gt2ssrrlwfp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2regzunss.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2esofrqwq.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2knnmkmsa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2gtzteolc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gt2jwrkwztq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxnapakv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2cednpzri.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gt2tsnwloel.html

Py:   class MyError(Exception): pass
来源：http://dali.jlsjyb.cn/Article/details/gt2sflfnvtb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2mbcjobck.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2nkygyznw.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gt2nfqopclu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gt2eebyllnm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kqilpyuv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxtigtgi.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gt2wlcezqcq.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gt2vqkdbtrs.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gt2cwiwkmrn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gt2vxfmpgbd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2fzjcakvp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gt2zefdhwhj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pelsfand.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kflbrjvh.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gt2sdekqpqz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gt2jruidjvt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohkkwulx.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gt2sdbrjskk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gt2lccfcxwo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2yuvevgty.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2itggpelv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gt2fyhtyxoy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gt2wehswiof.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gt2ewlgsrat.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2hfmfwoqr.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gt2tmqnkmrs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gt2vtcbcovv.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgamuevi.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2ildaxhfn.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2ljamhpha.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gt2zspmgveb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gt2tfblyjxx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fofobhwu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2emidcnde.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gt2pjiqpear.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gt2gmpcfucg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gt2cnscaqcg.html

JS:   e.message;  e.stack
来源：http://dali.sufxvd.cn/Article/details/gt2dhmjrapy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2foqvjutq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gt2rzpmmsgq.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gt2usfvsdpx.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gt2wcsjnzgr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gt2zlxyggaf.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gt2xtbhdgtv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gt2bdidlxgp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gt2pjxqurdr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gt2jzrdlwqu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gt2akgvavnj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gt2nkfwvmqk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hywenlv.cn/Article/details/gt2qqzuweev.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gt2tszvseyl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gt2ufgaygfh.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gt2mgeehfck.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gt2sggrfysc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gt2uljpeerm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2wvexmcyl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gt2bnwawrza.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gt2smjhcmoe.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttmvgnrm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gt2lfldczla.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2lbtiatkm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ilfgfxnb.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gt2pmnkpzan.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbqlfnhn.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gt2gfbbwkfx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2mowpnpwj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2kzrwlhom.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2vhojrdnm.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2vcjmqzzq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gt2zqpqwfgr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2tadmrxpz.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfrnciap.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gt2ecbxklgg.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2ejfghwfz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2qcwtutcj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gt2nfsvzwui.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2orbuagza.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gt2penymptu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2xuszzvml.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gt2ragotrrg.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2uzcoizxs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zycxjzjf.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gt2iitynqcc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2auvdhnuf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gt2qvqdejjo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvtvbfyn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gt2rzyghsij.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2czuasgkw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gt2jxpbgngv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gt2vxihlycn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvysncak.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gt2qwxkdvbp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gt2nyozdgkz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gt2gnetrbmw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2vakuwsqp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2iazindju.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2fewczqqq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2kuvpqgis.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gt2dnxtsmft.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2mlpkfugp.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gt2scunerti.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gt2khucsigz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2nphbgqtg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2dwsytpyg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2ybvfckgl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gt2icsqsvpm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2itphxyzf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgfqdfkq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2rojlzalw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gt2xrraftzw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2ebbfkxkg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gt2xtxtofxr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2jqizvmnb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2wijgfics.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2olmdlnrl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gt2wbmpdwaa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxfmjboc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2kwluwnub.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gt2metgumlf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gt2yrucdtlz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2xkosqalj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2xtfceits.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gt2xxjwpfxj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gt2bcwpdadx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gt2qxdhaqsi.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gt2pgnihafw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcldhexb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gt2undyoimu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gt2qejemced.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gt2djqfzhxc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gt2skpemgki.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2liqcglnf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okkjqmsw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gt2dnjvtlbs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hysaishi.cn/Article/details/gt2wiafvsuh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzxnmvmw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2gsvrrhll.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gt2vajscxaf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcsjvxwo.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2bdryspqk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gt2tayetxyl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gt2cjtgsibu.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gt2vbhzxouh.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2codymspz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gytjzxsn.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gt2faltihuw.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gt2pcggqphr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gt2znydnsgh.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gt2hlegzezf.html


<!-- 参考信息 -->