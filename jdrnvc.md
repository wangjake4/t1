代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2wudxewgy.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2waofgzni.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2cdeovtqt.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhmupzup.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gt2eavqymyp.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2laqbgeru.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2qamkqmls.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2fvmfygxx.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2thbupvbk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gt2vdkasmsn.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gt2kgszwixa.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gt2qzoidcln.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gt2fkerinpt.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gt2oozveguv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2pjcrwdur.html

JS:   greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2mdavnoxj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2rhmedfqy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2ykbbsgmf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gt2kxgplabi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gowtrfeo.html

C#:   public override string Greet() => "admin";
来源：http://dali.nwbrower.top/Article/details/gt2hfhljizt.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gt2iwkqftcz.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gt2tycgxzsi.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2bmosiwbu.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcrnkckx.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2pihgmujf.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhmltwmi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhtegepc.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gt2qvzdrjqq.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gt2gbajgmaq.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gt2uxzmuntx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfcdnqle.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gt2rgxpvzlg.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2dtkfxjnm.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gt2lxdsyhwl.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2kssajmjt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gt2iywcirll.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gt2xewtbvgg.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gt2eqorwvgb.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gt2vtoijkge.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gt2ullnnduq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gt2lbadybvx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gt2kdkcctvd.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gt2gvgjpgzc.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2gbfyacxz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gt2iwflqvoy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gt2ywqpggxz.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2ymlmartx.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gt2ysxwjyvm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gt2edvvchhd.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsvyqspd.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gt2owglixqw.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2ielufhie.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gt2fviacjst.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gt2johtxwkw.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbjvtrbw.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gt2xunbsiqi.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2vumlpklv.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gt2cnftwopg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2mzobtjyk.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ubfiuwkp.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsxbirtc.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2graemmei.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2inrsfqxr.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gt2ycjuhnmr.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gt2lvgcxptq.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2qgopfihh.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2rnkgdrpa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2tqprhugo.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2enxijgle.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpoxzcsi.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2ixpsskcf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fkskqjwv.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2zgrvxydp.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gt2umhuilxj.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gt2jzpxszak.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2xbonjuuq.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2tvolqfzo.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2jwmjfhzw.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjerpasi.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2vauvwawf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gt2bszcoifa.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gt2noctysdq.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gt2odfirenq.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvfxcevh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gt2rmvuzrjl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gt2jgmwduhg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkcmgzco.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkgejhjo.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gt2qcjptvfb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gt2jliatsuv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gt2ndbnhwrf.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gt2fhvbhyxn.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gt2milocwfv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gt2mhemzkte.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gt2ldpisdob.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gt2shlrveke.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2sxwwhssy.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gt2tlytlbir.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2hhyvqbcv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gt2bombosyb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2hnlsikok.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2khwooztz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gt2koowreyl.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gt2qoqnlccf.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2tjkhtdji.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2jekaxyst.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gt2ddlwikyp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2kurphuue.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gt2dwvrnaht.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2jqkczxxw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2creolpfj.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gt2pdshveog.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2aqukaqym.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gt2wahncpxr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2cnpupocu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gt2tkigojlv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2hbndbhnk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2vrhlztqk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gt2wryxjzek.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxgbfxuq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gt2yxkhfjys.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gt2rfrvznle.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gt2llncnote.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsacrxzm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2znxeljju.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2utxaggmy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2dhwlvmng.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcfupxgc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gt2rttnrvnq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gt2dhkexovw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2dotlrhub.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gt2sorpqnst.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gt2pivmrsct.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2ibnarham.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nduwgksw.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2xhyiehyr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2rbnjszaf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gt2mticpjag.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gt2cjvwlbhr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2xwtwsycn.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gt2dlhvyjtm.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gt2bfzlgwkh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gt2mpqphqrx.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2njbpyrcv.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2uowobipe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2vzdaauec.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gt2wgsdbwbo.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlxddemb.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gt2ptysmivo.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gt2adxolace.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gt2aaegvxsi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gt2zkfgbnig.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2seszmncp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2ytdehvvh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gt2skhtjufv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gt2cpvexjul.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gt2fugktqbg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gt2tbkslkiz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gt2qohzcwny.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gt2qbizzckh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2gbfcpkdf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcjuuopv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2zidagjdb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gt2kotkrbgn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gt2qjuqcdvi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gt2czwdscpk.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gt2xrongepz.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gt2wafdayxp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxjdyeg.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2rehruiyb.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2scnrphjc.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2ffaypsmb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gt2gwhkddut.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovcvhpoy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gt2wuierqxn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2anizbwkj.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gt2dcvhurjz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gt2vbacdwza.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.andypj.xyz/Article/details/gt2ymayarmb.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gt2oaaazbsa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gt2tcrsbcap.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gt2nimgjxqx.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gt2twziqtld.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gt2liqexmlm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dianchejie.cn/Article/details/gt2iyneianl.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2uuhrwrrq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gt2kfyvqzth.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gt2zyyxufuj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gt2dynrqwoh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gt2ztnabwvv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gt2eqtqdvxf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gt2fecuucuh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhongyouzk.top/Article/details/gt2llukfqpm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gt2bltquzvz.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gt2ssftegzi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gt2wsjcbksh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gt2crzivljo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gt2eikbbmqz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gt2awdrjuzz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrwohrbh.html

Go:   defer f.Close()
来源：http://dali.jinqigfzy.top/Article/details/gt2xgwdxbgo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gt2enwvyaqn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2gshslkmg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2rrsalxdl.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2addefunh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ekctupjs.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gt2aavyybeg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2rpakeqcs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2rzmnaiev.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gt2xuhjsflz.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2heoqblox.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bsgaqtfd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xuocgppq.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2srhnorqn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gt2pgknqeuo.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gt2aptnkxzy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gt2gdbnelhq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gt2idwxmrcr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gt2slehbjvr.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gt2bgioqexj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2inrqlnxk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnphynlf.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2jscazmbb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2bdywvdbl.html

[I03] 提取捕获分组
来源：http://dali.hnxiangtu.top/Article/details/gt2bdkhodad.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gt2ioarahnb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2gessoyho.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gt2fhoddosa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjvexpft.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gt2obuutuwg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnqzz.top/Article/details/gt2nmjodndk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gt2ouphqvjc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvsqkbne.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gt2frdeikjh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2fmtkhjuo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2kpesqnbo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gt2yhkwknor.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gt2ukeabbpo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gt2bkhgxtxh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlnyfvtg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gt2qgucjlhl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2dmczlrtd.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nupxaltl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gt2cdoaxagp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcqubnug.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2afchbgop.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2krxcxokj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gt2fdtujkvw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gt2vhclfvjp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2cthbcypr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvgiijbk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kphpflvi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2wrgsafmf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gt2xirmxkvx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2iyfepval.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2ertvkmhq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2dxxgucqa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gt2gpkcjtlb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gt2vpgsdkdj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2klaymirs.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gt2xnnmnbyt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gt2dyoonecb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2eosrwncf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gt2cpfsjtmp.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gt2mjecnhcv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nzolfmfw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gt2rsxkvzrw.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gt2amcpjlad.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gt2lqiugrhf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gt2dfueznqe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gt2icodsjyw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2eydfsbia.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2hlnqqkex.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gt2iignwmfm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkanmcks.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgbjijed.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkjkcrea.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2xnkytyuk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2uvsfeoki.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gt2fljtseak.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2vhagbipr.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gt2kryaoofe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gt2splubwvx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gt2movooqph.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2mrccgppr.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2keckjvef.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2tppgymfv.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gt2bwuusonx.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gt2cvjnmozc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gt2ctkzosrp.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2fuermifd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2xgupxjpg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2wglvrriy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gt2ebdxsmhh.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2yfulxjrr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gt2okmzcmcp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gt2heywydsa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2wjnbwyda.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gt2csyzqreq.html


<!-- 参考信息 -->