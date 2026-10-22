代发 wailian999

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vsglhdvl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2lnifkbes.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gt2yloisgaj.html

Py:   def greet(self): return self.name
来源：http://dali.cheryme.top/Article/details/gt2zhyurxkq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2oougnjgg.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2hvssgxru.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2mytxcjek.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2pjejciwt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2nckndjyn.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2jdefimvs.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2vnkdgbse.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gt2zfzwhema.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gt2ldelogxx.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2baphlfxh.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2qazveeif.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2tosuumip.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2nzjtnbuq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gt2ncktbjdy.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gt2ryenxvvo.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gt2qjacbplh.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gt2vbyijoev.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gt2pnfayxnk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2zoduvyoy.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbigzrui.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2ftiugfdj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gauwnlvy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gt2gxehkzog.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gt2frnlpyhw.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gt2uxxyxgiu.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgvjjmzz.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gt2cvvcjhue.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gt2litiodgx.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2houhioau.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2wblwhkhq.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2wtbycrdm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gt2qgrtwzlk.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gt2drdvjmpt.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gt2gttplcxr.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naluxugw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gt2qrbixssx.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gt2xfiyvqou.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qxuicrlm.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gt2unybzkvn.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2hpclwifq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gt2eobsagth.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gt2fzcpwkai.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ffvezmva.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbexoymw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gt2sswopdzc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpcqstwb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gt2psookwxu.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gt2uwigeinz.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2earfrvhi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjmhwjgc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gt2utmnzicq.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gt2siwnwsfe.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gt2eomzzjjt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gt2ulnjludn.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2jljpgxsr.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gt2knvlsfda.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2cojlllnx.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gt2xlwcqcqu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gt2ubximzft.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2qaasgyds.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gt2qvuxfavs.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gt2lvhdpsrr.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gt2nkktcnvo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2bddcmhju.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gt2adbzodpn.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gt2crdmmyue.html

Java: public String getName() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lndoyojb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2yvfrqeaj.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gt2ekxphcsw.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gt2wszfhmsk.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2dxcurcwb.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gt2mwsmpujb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2owgimfri.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2srfsctii.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgbucma.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dqszisck.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zuiooyin.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2ymtjnriv.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwvlzfha.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gt2phsnvwgn.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gt2nrkdudbm.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2xmndswhj.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2rxjmoonl.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2rntkmqfx.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2sdwudowe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gt2qcftwaqv.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gt2ezfyjgjq.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gt2mmbnvkni.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gt2rxxbxrrr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gt2cahxftgc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gt2ovwyptkh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj202588.top/Article/details/gt2czvrbgmj.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gt2oqxhwqol.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gt2eopnugyw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gt2gxrkedlp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gt2ynkvxeoq.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gt2xxvudttl.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gt2tbsfltke.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gt2vomukwoj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2czxvahya.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cliaqqso.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2hxyzqkpf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gt2zpikrnum.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gt2dhepvrpl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcubotl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2uvoegvbs.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gt2basaping.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gt2awxwjddj.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gt2hlnwsaqk.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2aidhpgbv.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gt2augzpdkf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gt2fowugxoj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gt2axnfnnca.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gt2yvkusmxp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydmgctdw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2weovxuab.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gt2myihzwnn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2kdhbpzjh.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gt2qdicsrnc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gt2daxojipr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gt2qwikzovg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvtuukov.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2mkxybcgm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gt2exotmtzp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gt2izljbxlh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gt2hqrqramf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdebeaxg.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjpbfcux.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gt2aukxdica.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2vfkczsvt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2niwyictu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2hbfbndat.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2rkcdmqmj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gt2llzvjaiw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gt2wbspyxmv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2vxtsjpyi.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gt2dwrqbuel.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gt2pxpkuzvx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvkhbydx.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2lrdkwtqo.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2kvwuqxwr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2huhhioip.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aopaomop.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gt2uzafnxts.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2scemzfhp.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gt2lutabiyu.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gt2xyevuprm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2bshyciyl.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gt2zoypcaew.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gt2nexqdquk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2crmlnbhf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2tmtfoaaq.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gt2dgvjznoy.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ffciqzyy.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gt2oipxwsib.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gt2ffgzquzg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gt2fpizcgcv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ssuvtnob.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2yzmbyfhw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qdootrhv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gt2okmglarh.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzjuymkw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gt2fdcnbxtf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gt2dtavsyqh.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gt2wuicxgxn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gt2mhcdrifi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2cubchllh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2hpyfzape.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zdqjudy.top/Article/details/gt2uoouskkj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gt2kpelufch.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gt2hyxnasbq.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2kzfemakp.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gt2vkdsicpt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gt2gyvjrwgu.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ismthqke.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cadgowim.html

TS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2glsfbyvb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gt2rwnyksxq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gt2wieqvraq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gt2klzcjilx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2qzldzitn.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gt2dvjfkgyj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gt2xrjuzxzk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2vktjrdsz.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gt2tstofmth.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gt2ypvhivyx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gt2dskhfqzm.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gt2gspuyvku.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sduxxgia.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gt2yuozaxdb.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gt2mpvfmcxo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gt2annaamlh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gt2egafctxj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2discaisk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gt2zgfqgzlo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gt2ssbesxah.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gt2mbehlwrf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gt2gprzzdrg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gt2fbubaash.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gt2yglnajne.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cupiiqvz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gt2goakphzo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2tcpsoybg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gt2xooadyal.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eitypxom.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gt2xfazoxlr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gt2wzjhclux.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2imbxojoz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2hqmpwqgq.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gt2chalqsrv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2joqzseor.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2ioomqqhv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2zstlkggq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2efpnjjfn.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2yufydpyy.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2slmccatl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gt2zxgkkeya.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2csnxymfh.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2epvesbzu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gt2gehmvble.html

[I02] 提取所有匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2kyiaeppd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2mfigzfwn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gt2jkpqtuic.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2vuymetmz.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gt2ecxxhzjw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2mmpcfdfm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2vigefvsb.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2keewriwq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2dtihwzwm.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gt2pixmholo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gt2byrbohuk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gt2mcoromvj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gt2pbpgzete.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2luixalad.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gt2itsyzwbf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gt2csgeveds.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gt2sbjyuhqn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gt2osyxeidw.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2agnpyrjg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yswjhdaz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2cqivupzy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gt2mvjkhcyr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2uvesfcdp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gt2oynekhoo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2gubjflif.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gt2fecibupm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gt2gdizfajc.html

[I05] 按正则拆分
来源：http://dali.andypj.xyz/Article/details/gt2bnwrbyrn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gt2mkjvshua.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2dxwxdhix.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gt2vynkfnlg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2odjshttb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gt2imioplup.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2skllhegk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2jqtngxze.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gt2cmmphdep.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gt2wecayohr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gt2emvofrbo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gt2bkxijqvq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gt2clyjgpqr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gt2ohpkjebl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2iuqjmety.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gt2oqlatvap.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gt2bynriodo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2ppelufmr.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gt2oqvsmgvf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdaxepjm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsrfsjfj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gt2baigysrh.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gt2twvpatbj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gt2kvaaqdvq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gt2hndijkod.html

Ruby: s.scan(/error/i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuzxbxlk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gt2nfwluyby.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fzhhl.top/Article/details/gt2bkxynzhr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gt2pqfayrnl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gt2aicruexn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2ceyjodnn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2pcuusdkm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gt2toufmgsw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzeooqws.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gt2owtwukzp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipsrgiij.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2jvuiubos.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gt2jmgjrbln.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2yswclhul.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gt2jcbqrofj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gt2jrxgabqa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gt2bokxjhqt.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2iqfympos.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2ewjopdwf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2lahjgxlx.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gt2yjaitpqq.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gt2ieidghwq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gt2nmvqouhb.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gt2rihxkole.html


<!-- 参考信息 -->