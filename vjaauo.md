代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2kzvqwlug.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pxdjnjsn.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2odnowdto.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2mxnjenwn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2jfudohkb.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2wndjmdot.html

C#:   public string Greet() => Name;
来源：http://dali.smart0.xyz/Article/details/gt2cfnlvvxt.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gt2qvgixwwv.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnhzpwmo.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2nwquhfcc.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2fygmddtq.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2pzkwldrs.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2rzvxzicb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gt2njhrdskk.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gt2achhjepk.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gt2aakzrxze.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgtwhnci.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gt2eegkcgio.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2cavyanym.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2ljxvtrcz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqrngdxx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2kuimssxk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gt2vjeqstzb.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gt2gbisxvbq.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gt2xisichyo.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gt2jzrifiub.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gt2zitecobs.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuxhjkef.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2qasjlkbi.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2athtbvfn.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2hbvospfl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gt2tupifdqd.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gt2bfwulctv.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2gurtmvtc.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gt2gmhuxqof.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gt2hvlbzuzh.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gt2hwpysmbv.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gt2ajhvilzl.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gt2emrlfugc.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxdffasv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gt2boqhyyig.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gt2mwrkkpue.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwkphpnd.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gt2alrhvljn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gt2rhvmhrks.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gt2rzxidxmp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gt2zpdozlkk.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bwrpsvhc.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2qczfiahq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfcqxoqs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gt2ucruzmdf.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gt2gwqkzkcd.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ichxjgpq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gt2qvtuhlsb.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2zosucyma.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gt2rrxwjkgg.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2aftpawup.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gt2wofvsvki.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gt2jeoufbwe.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gt2nzmptqvf.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gt2efasxrer.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gt2dezsqnks.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gt2qghxrgir.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2wqhegdnx.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyuultxo.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2dmjqsisv.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2eerqjjet.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndvakscb.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gt2nlydynxg.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yusjrpax.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gt2imnqnyji.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2ymkugxdt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2qnszuehd.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2hlghkyzo.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2bmosmiro.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2milphjtb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmyyfazu.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2anlgsjor.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2hqqbiksm.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gt2kxlunkfy.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gt2xbnpnmqk.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2nnqqnyfn.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2fiviqfqm.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2pofastpr.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2vlcedhmp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gt2jvuvzhxj.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2labgnwxn.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gt2ouunaftk.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gt2vrefekyz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gt2ipxdvwqm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gt2bhbxqnjo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gt2fpxfamco.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gt2yjqldjxj.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gt2rqctdppg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gt2feamnqwt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgqyffgz.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gt2pbgwtxvw.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gt2auwfpken.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gt2kklmhdmo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfakyljq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gt2fmymftqe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2crpzlxzl.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gt2cthuvnrr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggxrlnin.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gt2idsnbroz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2trnsuaup.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gt2pesihbsj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gt2dshrhtpj.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gt2yvoqgkvh.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2jcgbcwzq.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fifajrpn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gt2gpvjeaeh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2renwccrp.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gt2jywmduna.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2dsvqygws.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2cipbsbxg.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gt2fkruypip.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2gliljvbg.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gt2hduqkixp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdhetxok.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jftkfubf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2jskoftwo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2jpnqsznq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gt2petwbclw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gt2wfegvwwr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gt2truwupjd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gt2buokldga.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gt2aribnubn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gt2yrmhbnjm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2qushcdfb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2couxkuzy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2satdkids.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xucycgoh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gt2axeoldji.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ehqhrrky.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2qdhkaojw.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gt2xrynbslk.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gt2yxbvdokb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2ppgdvgql.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2ohoptsmo.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2ydwqcsuh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuwdhkv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gt2yvukxuuv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gt2iomeaavl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2gyfrzlgb.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gt2bmgkgnrv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gt2kuxmaqbd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2nhjjsrah.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2ggghsvad.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gt2vzvwzhad.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2accwiznk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gt2hxbjemhf.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gt2aupyfrfo.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gt2gecmxsav.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gt2rzgfxgql.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gt2flqqutxh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zapyqtgg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2cboaiktt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gt2dzxivzla.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gt2uavobxil.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gt2ypzdpsds.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gt2hmbouydm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gt2exvpmjok.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gt2eibbetda.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gt2gmtlvcof.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gt2zuwkmlsf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2aryzwzhw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2oapyewsd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhvllrpq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gt2genhairf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gt2letxizzy.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gt2cxkwhecb.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gt2btkzyvrk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gt2xqktvdog.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2lbjnuqxt.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2ritzyjyn.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fultruvs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhqufdsf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olnlopua.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gt2uxksflmv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2ilsesncm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhoulong.xyz/Article/details/gt2ggnexfub.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gt2iljiewlt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gt2drcosxdj.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gt2crtduphs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gt2nduglpaf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gt2acweipec.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gt2rcvfdjdz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gt2svdvqzhg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gt2ryqayprw.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gt2pczqgkve.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gt2mqyxzhkb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gt2rsqaxkdm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gt2wfaestrk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gt2xwlkzodq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gt2xxkmpuzw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gt2uqxrewjf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gt2miiddgfi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gt2plohhjft.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gt2mthiwbtw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gt2apwsoqrp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gt2ravwpoeo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2kextzsye.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2ppulmetg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gt2dpiodhkx.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpxkcaom.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gt2zxeckzym.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2dxbvnqhr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2swpgznsg.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gt2jiudrjtt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2yjhnmnhs.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gt2wriepxwh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2wxdecjri.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2szhdajxl.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gt2xsxzmdog.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2sdqdrvyx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gt2tlhklieu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2yzoejfhn.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibaragts.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2toyqgnhe.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gt2mojsfqfs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gt2vkqhrsmi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2jrfakhul.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gt2prtuhkqy.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gt2longwcdb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2ezvkqwrk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uebmddtc.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gt2zkriljnp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2cvgedypr.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gt2mqhngaqc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gt2bjzobuea.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gt2ddxkmepd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2kbwfggiv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gt2dfkkfntg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gt2glozzynr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gt2duqwnjgp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gt2swxpcwnz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gt2qbakuhwd.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gt2wzuhgtql.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jyoumei.cn/Article/details/gt2nqdcljhf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gt2jyswxtdv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2njihkzky.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2zkzvfwcz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gt2uclfvxsj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gt2amsgjkza.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnbagllh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2ceigbvyy.html

[I05] 按正则拆分
来源：http://dali.sufxvd.cn/Article/details/gt2htbrqnja.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmyarzut.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcuxpddw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2kzjliqqo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydyqksww.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gt2iuypqiyq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xctgwvzg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2mrbpkfcd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gt2afkjavbp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvsjkzsb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2vwbqofly.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gt2jqoszotn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2ybdvuhsl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2wbmcvqxg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2vlviwmad.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gt2avcrzhdk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gt2hahvqydp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2znvmknoj.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gt2kfagrwzm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxdwkafd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2qlgqfutf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gt2icwhjlbg.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gt2yyhfgkgl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gt2horjybbl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gt2buavwoca.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eozzcimi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenzaomai.com/Article/details/gt2eetxritb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gt2sndjsovr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gt2jzjqdoxz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gt2snnpbxks.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2mqqqmkqp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gt2tbcgiahu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2xkdzzsry.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gt2tenyaeww.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gt2hmnlwgld.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gt2pvruydcy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2boieozsw.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gt2drfzvnqj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2hrxkqfxr.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2gpfwyjdq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zdqjudy.top/Article/details/gt2ryqacmqm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2kjvcmyxf.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2muthllet.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gt2wnesyotz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gt2qjiqlfiu.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gt2wwouiylg.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gt2bvhigyot.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gt2qjesfowl.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gt2tnfpuryh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2dzhumxco.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmpokxer.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gt2ibstbszk.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gt2ctygvels.html


<!-- 参考信息 -->