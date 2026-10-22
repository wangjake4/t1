代发 wailian999

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2zhcvqubj.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbpnzzyh.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gt2asmxbtsl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gt2qfgjftmv.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2whtchkkf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2jfgbobdv.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gt2owlgaarw.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gt2arlsfxsn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2upalihmf.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2clyiiszb.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifuijzot.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnfdquwb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2nfmjeqrw.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gt2hjdheywd.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2kbgnbmmf.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gt2kdexigsq.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfdfsirk.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2rqlkjygg.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2kshfccxg.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2soemiexb.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2yonubgwt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gt2ifbalvfh.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2vmmldtye.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gt2lwyvndky.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gt2usclbthv.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gt2xgfvcraa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2rcotevdf.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2qtchdafx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2dktkpgty.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2piucmgfb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gt2aobehqqh.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gt2tltwxqkl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gt2uwddgbmz.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gt2pdlsdimq.html

Py:   super().greet()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpenhskk.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdgkdmeo.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohuogoqn.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2odqwgana.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2akrglyxl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqdqdfcn.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2tvtikrhv.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gt2djdefqss.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gt2ldwqhbwj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gt2coqqvyub.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2uspzetof.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlblfval.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gt2dfberekj.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2mmtckkka.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gt2wolxycqt.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gt2loacahsd.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gt2ehumtdqv.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gt2jyfvcefz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gt2mxcwyxvc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gt2ywuibsln.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gt2gwjvvrcg.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gt2timpzeia.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2anzpmmvn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gt2xvvultfe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdxcbtlw.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2vetrtlft.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gt2wfcwenmn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gt2walwipgh.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2dmdgjvac.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gt2qrjbfivc.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2wjdwvmsy.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgkyswvi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gt2cygocxrp.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2tqtmzbyz.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mljhjlgv.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gt2lpwprlnn.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gt2urghbyfl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sehieuhc.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2vlspgokl.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ndobmtxr.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2njtnrufr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2yuodbqyi.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gt2ujbybaif.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gt2ikgnebdz.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gt2oyqzamjz.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2fokwvmtx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xetbihet.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2iajyajys.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2expuxijk.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcmzxxfi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2mdotdupg.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gt2sqlhkwyd.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gt2dalipseb.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gt2wvluhelv.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gt2kobffarj.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paxaeubt.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcvtfdzr.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2asdtyooo.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2zpbszsds.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gt2xwslwrqm.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gt2emezppnk.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gt2pdfgqgag.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gt2kvfbzeug.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gt2lkmmylic.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gt2eixheans.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gt2oyeeuezi.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gt2iintkmxb.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gt2uhzjwpad.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gt2zcniibtv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gt2isiwkwjc.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gt2zjpkaalz.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gt2znfabzgv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2oixalxnj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gt2jznxkfit.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gt2ptmbtsku.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2mcrdtfdl.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gt2myrqnujs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fengsongda.top/Article/details/gt2qaspqiqo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gt2grrvgesm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2punjlpma.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gt2edohufub.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2plxwncxj.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gt2owyfciui.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2ybzahikm.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmwthagv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gt2woydhjzj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2briwdgrw.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikfvtwkq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzbznqci.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2qamtguvd.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2neweusbm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2tixeljgx.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gt2gbzjqszd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gt2stfdjaii.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gt2bkmccyba.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2omhluoxg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2syhixwkk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xupabknh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gt2nlasdqpp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gt2kwjlfqcf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gt2qcrfcjpl.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gt2rlwqmwpr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2cupreqfu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2uscsurhi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2odhyrslq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2uafnsxuf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2brjbvshf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2lfhobfyz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gt2hqlnmpju.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2gaejhexv.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gt2ebqtcvqs.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gt2plqukvoe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dsdqhech.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfompyxb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2uxdofiac.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhndlqhs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gt2knczmiut.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gt2rgmxcjbu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2gdtfkvzp.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2kxlqpiec.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gt2yqnlfyco.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gt2booecskd.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2dprrpqcm.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2ourxduyx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2vurryufe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gt2oqbinwuv.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gt2gicsxjey.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gt2bfwwizzt.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rluofbox.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gt2ytmmlcbs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gt2zpxdztxk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebxesgux.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hccefeol.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gt2rvqfelec.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gt2aicfytlh.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gt2mhpnbfav.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hryqmbex.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gt2ivumbdzx.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gt2ikiwmccx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gt2jdnopbff.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2eldimzsy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2wbxkgwfw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gt2biqxqknp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gt2zqoifmsb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gt2jzcilism.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gt2epljgohm.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gt2oatlbsgy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gt2rtjjbldp.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2zejhbszg.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2ilbzaytt.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2mpdpvvft.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gt2dtbejnju.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jianghu66.top/Article/details/gt2agmmvtuo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gt2mdwyblid.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2lzpzsxpy.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xztskift.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gt2zxvmsbpk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gt2gkgtvsia.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gt2phyzawbx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gt2sagrsfcb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gt2viuyluxd.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gt2wqsqnmeu.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gt2lqwvuppo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gt2xrpxrouy.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gt2mfcghndv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbvodoim.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwwtqxpf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gt2eboaykuv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gt2jfkztvxy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gt2oszrnqzf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gt2vabwxuza.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gt2jidzuuyv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gt2eickybsb.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gt2tupwmijk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gt2vqhuetra.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gt2njyhcdhl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmbrqzt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2uxlnepim.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gt2cqkbcbru.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gt2iwzbbese.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gt2yiavdfik.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2wgenxagz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2axhwmsee.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gt2iinyndrr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2puapuqvr.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2jmxrhdvj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zyhqonlw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2azbkdhni.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2xfpdmzqr.html

TS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gt2edvjsbde.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gt2urhwaluv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2wowomlml.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2ctkdpdvh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2oxqjyuxt.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gt2fdsprraz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gt2brmdlfwz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gt2nulpkepj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gt2qoxyyysh.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gt2gwhibjtf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gt2nfslknsb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gt2jrnhfcbu.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2getjlsey.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gt2iqftafwb.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gt2rlijtqzn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gt2dztswcfj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2jcwbeubv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gt2tqqobrss.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2ccgjebgz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gt2clabpchr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gt2exdrcmjy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gt2gmzmwhad.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gt2wktyvkae.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2iptmlzfb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gt2wvqkkgqb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2eegxxpsh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqadomxd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2ethuwsfn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2luhilnir.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gt2ggrdybbi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gt2rhmuzgrs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2wgcadggr.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2drdcwell.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gt2rvkypiqo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldghwtpz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scwazpuq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2hguxnbiz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gt2nuhznwvv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2ltjcvndi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkuftzfi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gt2outtqibk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gt2llmkztey.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2sqkrhpnu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxtcntwf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2ltyufmtq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2yfsehnmv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2dtncuczy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gt2rxpfqovn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gt2ytsmiamb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2rcaqouzm.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gt2oqqmuqtb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gt2wvkqqupw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gt2cngtgvvl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gt2ivqrcnmc.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gt2dmaubibn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gt2rzctzcuh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsmcaypk.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gt2dzfxrxne.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gt2vyydjioy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gt2lhzmvwfz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gt2cybeughl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2lirhhyns.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2cbcibhdw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gt2vnnuyrkg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2jlgzdbwp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cqqwz.cn/Article/details/gt2murpwxhm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gt2jrjlzzvc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2pimaqplt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ynouaceo.html

J. 日期与时间
来源：http://dali.aizwys.cn/Article/details/gt2lpmygtng.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2znzuemsh.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gt2bxqhnhcp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2mqgjmndf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2lhmlskis.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfdgwqcu.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dyssjdww.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gt2dchpcbcc.html


<!-- 参考信息 -->