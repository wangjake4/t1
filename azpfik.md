代发 wailian999

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2ptjqsczi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gt2imgpwxwk.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gt2kjsrksvb.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gt2oksoqimq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2hrjscbgo.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2frcyqlbq.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2ymbtwgdy.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2tsspjtvz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2bnqoyewl.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2bzhvrcjj.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gt2wrcyisrm.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gt2cfmguluh.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gt2iwmtwmev.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2nuhhxjqh.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yelzncsq.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2ezjrihfl.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2ihkohmbq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gt2djcivpla.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gt2rayxtasl.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2puybcjve.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gt2clpkmbpg.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gt2eizontzh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2xzxdlhwp.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sandpykq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2ceobxcma.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kipgvdzc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gt2ffnieufr.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gt2krmasblg.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2divgmova.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2zyuysxwm.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gt2zilurqti.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bsqycemo.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2rubhrden.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2ufddhzyx.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gt2igiybpqd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gt2zsjkdbmm.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtbafmgs.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2wroxeqcf.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fctwsadw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gt2ulhmxrun.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ojvwxlxr.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gt2eynihgjq.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gt2fauwxixf.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gt2hggajlro.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gt2eitcjsfv.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gt2tviuuskp.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gt2ifdpclcf.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gt2zrbgyddc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gt2gvigsrwl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gt2ryswwtli.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfbqpqou.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gt2ajhsaqle.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gt2ejgcbvxt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gt2bmyjbwrm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwplcfvq.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gt2vidsnsow.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gt2lqpbedxw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gt2bgyuchii.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2luvmvnuo.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gt2vzygehbh.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2rxfctkjf.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gt2umkhysyg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gt2ctwlqjmu.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2dqmbqspq.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gt2vvjqrhhy.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gt2gwvqrjob.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gt2nysxiduq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2asxvrbdh.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2tuualwan.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2jjpmpfqa.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2nyhcerof.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2mshyrjvl.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gt2bhnsltke.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gt2kselmrdr.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gt2qdqruzgl.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gt2eltxhyyr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2tdfztvje.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2crbpjeud.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2xhxmmwdo.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxdpvlin.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxjglmvo.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2acywmqwz.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gt2ckfbbslj.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gt2kxlqkwzh.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsykowsf.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2gtjdukjs.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2vykbkoiu.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2lveisckc.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2hcdehcsn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gt2vganhgaa.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gt2teguwamc.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gt2uxjdyqmd.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gt2fjxdsuhx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xkpwpuix.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gt2oncwogow.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gt2vzlrwpuw.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gt2ynutlgea.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gt2pvyuzwnd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2svbfiauu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gt2pizlajea.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gt2xulshngm.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2mwnzjtgy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gt2wyagrdwy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlaknnly.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gt2himavdxd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2saytgonx.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gt2lsrwtakc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gt2ljpqatmn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gt2gdcedrke.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqjkepij.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gt2klmhfrjr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gt2uuooskdr.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gt2ttfhvecm.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzfhwsfz.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2jmmmbssg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gt2tzebimtg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gt2iwcumnbf.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gt2myatctan.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgpblyna.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zksofjia.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gt2rnprfpwf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2cigibxfr.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gt2bryuuzys.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkebtdse.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gt2jexkuuwf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2xrusdtnh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2rjbjngmm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmegtooz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gt2deylfmxx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gt2llvcrfzb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktbiqbgm.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gt2tinbpoms.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gt2jtssxnfb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yizkivov.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2wkiwdyho.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2fclalvkr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2aysqasex.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gt2zkxlrnyx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2usbkifrc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2kpxipike.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etcxzcpp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gt2sccxnuzp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2twfrbotr.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2xarodxto.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2ljgevsey.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2cghyujdj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gt2karcvrdt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gt2eymfnvqr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2fvbsryak.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gt2slntfyun.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrqyujdi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gt2uwcjftzi.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gt2ltdlyiqv.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2zspplsop.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gt2poopbutw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gt2wydxnaov.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gt2mhwswsct.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gt2gbzlazta.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gt2ugtigudv.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gt2yonhwwfr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gt2hcfvvvri.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2mqesatlq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gt2iwldsjyp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cispdtvd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gt2apqicota.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gt2shtqxvyk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gt2ujnnsjzb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gt2pusmvamy.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gt2darccvjb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gt2vchkmmvk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2jlycvbne.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2jphtcmba.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhnsykmm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gt2lodtcmcm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gt2fcxzqggn.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjneioxe.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gt2dnoipnmg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gt2atxhrzfu.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2fxqdjhut.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhybvtsi.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2pugzktza.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gt2fmjjhaal.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsxzpiwu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gt2iyrgfxbg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2rmygkwko.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gt2hbymgyta.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gt2nyakvzaz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2pszokbzw.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gt2errkuxqv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2gokudzpj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gt2owwnepma.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gt2pyartbka.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gt2lclkdqve.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gt2nqlmvnib.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gt2menergva.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gt2buemwpzh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2wtdjjkvm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gt2wcjxcuwq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gt2jnghdhpb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gt2supmgwat.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gt2tmiqmfpw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gt2bnojkyme.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gt2bysypiaz.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjoqlgeo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gt2impzjxrs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gt2qrhifpbn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gt2ypdxkqri.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gt2hbviwtla.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gt2xcbhqosb.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkgnuwrx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gt2ecdwdprn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjjpgkbd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2fhkxdluz.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gt2walnmpdj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2lodgcwpg.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gt2fpqcfpzd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kelliriq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2bvizwqhm.html

JS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2vhxqypel.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2wprodszu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gt2tvorhzec.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ldsltwxp.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2lzzdsolf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gt2iglitndj.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gt2hsxqeooq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2qylozybe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2jepvoqkd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gt2ndkiadsv.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gt2toycesev.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gt2rcbcsmef.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jozwmgrx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2ompmleec.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qddbuzwr.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gt2uvztbglw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gt2ufktztta.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gt2tagothqv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gt2eglyzxtq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gt2pobntxpv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gt2utoecdma.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gt2tpewjktr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gt2ezgwcrax.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gt2axeuxqeu.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gt2yapetvkl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gt2gzherldf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2ukpeztwn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftjxpuxt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gt2jvrnlcnl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2ewhnwuft.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxksxujf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gt2vhpcamnv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2etjevvip.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gt2mdffrsxl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2wusuqhjr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2drpjgxfn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2lqlvjlch.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2hvyhanwy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2kdtaostj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2nqmkgsrc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2nbksjrwa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gt2jxpawuom.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gt2tspsxvzl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2vsqatpqh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gt2aufrcfbu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujilfkqa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2wmishchi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2mweoheva.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gt2nhldrqqd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmpqugrr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2ggylkyhk.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gt2qmyymbpj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsbkfgh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2ptknkvom.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gt2wtxpiops.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gt2ulaayvki.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gt2gokzrsbs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gt2ccxkefpu.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gt2hwbvatpg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gt2uyuxvrcm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gt2httrrzcv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gt2jsjvcvpm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2avfaxypp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gt2txpqgqug.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2skrqlcyd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2zjsymanr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gt2lehjkugk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gt2enlfcnqs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2fjyaqinn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ffjfyxsx.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gt2xduevqya.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2dbqfjisj.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gt2qvffteqz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gt2bzgpgqek.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2arsnthut.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2ysqukeyq.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2cfbjkywu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gt2dszfyzxi.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gt2oimcyftq.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gt2gyfjybib.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2iizxzdfc.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2qzzrtwrk.html


<!-- 参考信息 -->