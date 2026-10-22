代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gt2pzwpemgh.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ocargwne.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2tzkqlmif.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2toauydxp.html

Java: class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2ohihyzal.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gt2uuazfumi.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2zurqzngu.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gt2pxzvency.html

[G06] 重写方法
来源：http://dali.tanke756.top/Article/details/gt2nqafbfcg.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gt2rbjbqwph.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2byyrzred.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2gpxojexc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2sdntvvoe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2zyvkcxue.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naovvuch.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gt2ufntckfj.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gt2inczgtib.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gt2vdkqdbrr.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gt2jmcvwotn.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gt2hwwteuct.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2uexirvdb.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2dzetqmob.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2uwsadevq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gt2jwskmorg.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gt2uqhlnpfo.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gt2eijwmehq.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gt2mzmlcdnk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gt2oapktysv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icwyvlzp.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gt2yqbvxsyg.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gt2xfrxdjjz.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2yxiebafe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gt2xicqzugx.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gt2swhjautu.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gt2xebptxoq.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gt2ihyyrywe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gt2liiexaic.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kzfkuapi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gt2koqkitfk.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ebeadtww.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gt2mpnycafu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gt2bkcevxzc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gt2uppbazsz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2masvxtzz.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gt2eemnhcrw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gt2axcatuyr.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2mxjatmhp.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gt2ftnznabd.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2zbplcwju.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gt2asamnrbf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gt2xrlkcwam.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2nkonyclm.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gt2txnexldw.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gt2bbyqxmlt.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gt2obtkwstq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2jkrpnpyr.html

JS:   get name() { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2walvcces.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2acnyqsgd.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2hpotriyf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2ekkiarll.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gt2fusxromu.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gt2ygvmmcbz.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2uxxdtaln.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2heoppgwa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2fxibpkvg.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqwqgsah.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2lrupjjgo.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aowdxtwj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2nefqscow.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2mbpwmpvt.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2sbseczay.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gt2zgipqcsn.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vollvfad.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2nmsblktr.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2drnjgttp.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2idfomayg.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2bqpsbkvo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gt2kwxitcgh.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gt2yxsqopiv.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gt2gfozvibi.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gt2bxgynmqr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gt2sznkvdfl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gt2utazjreb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcyokvvj.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gt2myjmjmgn.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gt2hxkprujq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gt2thzghrwl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gt2nyusmmis.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gt2fmidwfqe.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrznredp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gt2pfxbkgvl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gt2gcrznieh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gt2jusukmyl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2lmsbrvoi.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gt2wptsevdc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gt2srfajsds.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gt2ghblfeei.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2jzdtclpf.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gt2jhgihrdp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gt2fbhzrjlb.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gt2ebsacxmc.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gt2ywopwsxz.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2jsbkowlz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwsxowet.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gt2gqjlqciq.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gt2osioeais.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2ufvqusld.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ybxawgoj.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2ciouphrt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2nfvceswj.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gt2kacigxzc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gt2cxbfzhgr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gt2ljunqlyg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2rqehymxt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2hhubrhaq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gt2ypgcicdb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2iblzwbug.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gt2uwzzxmgl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gt2axpiiaio.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gt2eryftdff.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gt2nzwywcrs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2vdvaajve.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2kyddftsm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2aseuncwt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2guyhbvtq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gt2egqjvvkf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gt2aolknqdb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqvytmle.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gt2idmrrlhr.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gt2whvcdqrv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2rtnvdscq.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwabaakf.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2aabfmini.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2cbxqcgbl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gt2wckswqnc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gt2rroukcir.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2irnxmmik.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypugmwft.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gt2klvdqlho.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gt2klsiacid.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gt2hfqqsnzc.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2umkbyhrn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2kthnoasq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gt2ytbbrvrh.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gt2xttbipym.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gt2sdjzubez.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2guvhyqia.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2qdlawkva.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gt2rbbkdrxl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzrcxqvk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2evrcwgld.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gt2iadlawdj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gt2vfrighya.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gt2jalhcfls.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocrfvdld.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gt2jexfxwua.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkbsnpgp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2fsefnjwy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gt2avhcpmwi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gt2jaqlvfmx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xobtbgos.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gt2btvlxnpo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gt2olkqlwbf.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2utrgpdbb.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gt2qxwtqwnh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gt2qgpoovzl.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2fkcuxyui.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2oyjgjxul.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2cqxlgbjh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gt2gucnznhz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gt2yaieesol.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhoaxhla.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2fubcmgwr.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gt2gnpsgifg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gt2dmeaorfk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2dkslgefg.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gt2iiqmsyqq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gt2wowwpstu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gt2cegsvjrs.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gt2qybswxgl.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gt2afuswryq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gt2egiltyha.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gt2augvsknb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gt2fvixxuzh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gt2clfrpesm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gt2weajnnur.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gt2nbvlafwn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2haochxco.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gt2hodnusng.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfnremyl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gt2bjyyxsol.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gt2gijvlfxq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gt2mahvksnv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gt2bmaimbsy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2sefedrqo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gt2cfjgsany.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gt2bnidekqu.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2fmuzctvd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvbhthgj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywxfxdsa.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ggjvidea.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gt2syllffwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klgvjouv.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gt2jsgzsuhe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gt2gtoubecm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcbviyjf.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2rwrsuqli.html

TS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gt2uvokvhzr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gt2sktwrpgq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aswjklmz.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2msjeauoq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gt2qvzxyekx.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gt2eatsqjnp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2ymqystny.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gt2jywmmyfx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gt2rituphlu.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2duvfwziw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gt2caymnuld.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gt2xveqesio.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gt2fpjejtub.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2ycnddorx.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckrlmmnp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gt2yzvkharu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2adiqjbnd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gt2keumuzem.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gt2acgewwkp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gt2rouqklya.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gt2gkwobxko.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gt2snnikomn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gt2evivtktv.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gt2vxcaeyzn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnhliqfj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2sspncayy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2esguttlf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2rgzfnokw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqdbaaed.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2edwytmdy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gt2dmtfyiby.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gt2havcnyxy.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gt2dcyzjzvz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwdubhz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2mkibqrwx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2vddzrvdd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2rxtozpij.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gt2ihrgwaog.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gt2wmqftmbu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2iinhptko.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gt2vjmvbgot.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuanzx.com/Article/details/gt2aatuahwq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2vyampbhn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gt2kcqunobc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gt2doymuwwo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gt2iqrxloey.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2gqjcqbrv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.kuanghao11.cn/Article/details/gt2fhwxntip.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gt2nutfkwht.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2uletfetd.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gt2rwqiivdb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gt2hbskrnwu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2uyaduilt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gt2fkswogmn.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gt2uokjyxxp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gt2gsweknyc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gt2xczacvmi.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gt2cngkskah.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gt2llwoqubc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gt2rogzujnr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gt2xlnsucdl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2yiydschu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2jwdauqzl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2ffkqqsel.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gt2nlybhrcj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlwveabk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gt2tsvzhpbj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gt2ysgjdyzl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2mxiwudus.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gt2jvgqjhok.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2zxdiupkg.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jodnsadc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gt2ozbdhwdi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gt2gyjqwhdx.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gt2dkedroio.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2yxnwzlgq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gt2qrlupifh.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gt2acriemit.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gt2pqbrlcre.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gt2wsigbfnl.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujbfowbe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2xptnktiw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2gqlrepca.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gt2ookmgcju.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gt2uzmqcpwc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gt2ilsblshd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntjxlpgi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2ibmcxfbl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gt2qdiuwrqa.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gt2lbkrlkdd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jlsjyb.cn/Article/details/gt2hqeewkyd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gt2bpeldonm.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2tmppxaey.html


<!-- 参考信息 -->