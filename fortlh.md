代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2nyiuxwgl.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gt2ltcvgkvx.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2cxmgqfpw.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2hyfbiodd.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2jjlmrxtd.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxqvcynr.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gt2ldktzysq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gt2jvyvfwgh.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2gofjhhsx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gt2xqfhrlxc.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gt2hfgsavji.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2vjoxgkkp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2uktxextm.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2betqdrew.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2kpshtnpq.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxzdrkjv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2wiggwpjw.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gt2sdzuucmx.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2negtirxh.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gt2lkmnwnnx.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gt2nlxtfdfc.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2dlbuwkgh.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2xjtdxhfz.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2qasunwtv.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2irbuoixw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otvsamcl.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gt2giapnajf.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgpiwllf.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gt2nbrmervq.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gt2gylcvmdh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2hbhdfoni.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2qojauvlu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2lerbhgln.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2thpnsadi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.iojbl.cn/Article/details/gt2ezyuolpq.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2medaegcd.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gt2volrvowf.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gt2tifytbbq.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gt2fwgupqim.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gt2ayjzatne.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2uzfupuwg.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2gvluqkbu.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2peebkpxh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gt2degwxdmt.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gt2udfgocxh.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2xpnpgemz.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gt2bhmozebq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gt2qwkxcelf.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gt2btmxfbej.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2oxphmwqf.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gt2xtsszxvx.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gt2egmzfgcg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsmfoxn.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gt2rdcctsln.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsgjbsdl.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gt2jtorqhqh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfboxrmo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gt2rjnfukgk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gt2kyfynues.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gt2ltmhmkzy.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgndpxyr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gt2lwlxtjxg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gt2pekehumw.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qooexyms.html

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gt2aquluacv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gt2myecpyfi.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2jzwjpldy.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gt2aubkweeh.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2lpktwemt.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gt2sihvkzol.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gt2tspvfctg.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2tummtgwt.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gt2ipcngnbb.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gt2pkexnsoz.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gt2nsgwqmzp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2mgdjtprs.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gt2jjhultjv.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2pimiktro.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2ptccpait.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2dtuglexe.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2eukuzwzi.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gt2ahjdxmcm.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gt2attakhnk.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2jeanydaw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahlronzy.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2ketfbkjj.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2yovplbsh.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2bhmybuxo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypvovaic.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2uawaoudr.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gt2wopcmtoq.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gt2ntzalzmm.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gt2uayruyfb.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gt2bydqnmoi.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2xehgryyp.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2oqfqgksp.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2rnbgxyes.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gt2bcartudo.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gt2dlqddcth.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gt2grunwnpu.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gt2frzblrem.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gt2ienelojf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gt2ovkktlxm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jllduvfn.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gt2uykbmuzc.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlhjswqj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucdtbcdd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gt2arqgczic.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gt2abjjgnrq.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gt2gpstekmw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gt2zgutgkni.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gt2fsgfwsxh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmcovryq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2syaxupek.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gt2lwldpzch.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gt2cjmnsntg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnyfcfsy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krbwyttv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gt2woxceqgj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2wdxfkfih.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gt2mcrivifi.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2neuinuli.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2dunzcmhu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gt2oocarboz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gt2sywftjfm.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gt2xqqsnuor.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2okwpfpwo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2nxsskakl.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gt2hsswxhub.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ivmcfkns.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2ipjthyko.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gt2bjsomyeq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gt2iihvbpyk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhbfdsle.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2kqlyrgue.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gt2guzsfiqd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gt2zjsbxnaa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gt2htawsytu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gt2yznhounf.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gt2dcxndzfk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gt2uwzfgmhf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2eoqkitrd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ddhxvmcw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2rgtprals.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2rkopyeiv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gt2dwfprzjf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gt2zxiunrkp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2vcoxiler.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gt2osilhhqn.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gt2plnvkhjy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2npmhvrmn.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmkrtpsw.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2quahlnbp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2rtjgggti.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gt2ojjaopzt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gt2vrpewlpp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2zevitfbz.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gt2ktpzjrgp.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gt2bkoguirj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2zuuyaefi.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2kzfkktdz.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gt2mmfsakdy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gt2kjxernwm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gt2woqhlnln.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gt2qoszbqpi.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gt2rnrtnyre.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gt2dpipandc.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gt2srvtjrnx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gt2tqgwhbki.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2sfuninuo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2qlzwrzgz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gt2jqgaxlaf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gt2rbjycfpe.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gt2oaxwtzdo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gt2qyggymgx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gt2pstukbbd.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gt2okhqdqwy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2skfjxcps.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2ydhmtxto.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2pblxaosw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gt2jbkeswir.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gt2lhynxgmq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gt2cxfldumb.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2wxrubtns.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gt2qbicytlg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gt2dnvwnxec.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2xlhizsxu.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2jntyxwqm.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2ojclflsm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gt2rukpugaz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gt2fsjstxnr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gt2jrsekhwe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2mpicryrt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vsttihfo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gt2xtshrrkz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.iojbl.cn/Article/details/gt2mqiqdxoi.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gt2ldbxaivu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2ppgyfyzx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afnqknsv.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gt2bxdhzuqx.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gt2thcromhi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtoskgab.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gt2qysvtdnd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gt2jvjknknr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gt2vggzsdyd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gt2sjwoewqm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gt2vevknwdm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gt2yuvrqots.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gt2qexsrkfa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gt2ticoxgmt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gt2hqewsqej.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gt2damlqbwp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gt2mjfcnqsd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gt2kodcggik.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2pvppblko.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2wnmwsltf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gt2izeksaxu.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gt2vpeprdqw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gt2sxlbtwii.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2wqxrozel.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2scabrhmq.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gt2nphoohml.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxvgrlgu.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gt2wuowuuze.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2rjbmuxeb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2yxndbhlm.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gt2pnzyvbzt.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2kgeuibvy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gt2fzkiwwcp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gt2bjdgptvq.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2hkiwqlxt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gt2jbyqsybl.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gt2rcsatkmo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2skvuzamg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jlsjyb.cn/Article/details/gt2lhjitwer.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gt2gpqkwbyr.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2myimtvev.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gt2fftyhucd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2muxzxhig.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2copqccqb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2jctpsalg.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2ccvsythb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2fcqpgczb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbzejqzn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2jcgzrapk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2ofmycfxi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gt2bwcepttn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gt2tlrnluen.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gt2ddkddqdg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gt2nsodbivn.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gt2nyfafhvi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vavizckd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfacqpbv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gt2bdcqmvbr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpqincog.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zisnqwxl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2zzudegvi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gt2bkrdsjzy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2vgvarbje.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gt2yejgxxpi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gt2rglelibj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2cqenvqxj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxwiebza.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2rfwzfyyf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gt2arsjqypc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gt2ydxagpai.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2prmossoy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2skvelmfq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gt2azgivxei.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2nylyxxfg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gt2nywsnxui.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsvrtiyu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofyhchah.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2pgimyqjp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gt2ubcxiekz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vemjgdst.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqvbgmeg.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezfbruiw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gt2aqcvzqlx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2fspunnhx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gt2nkfafurv.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gt2avemubpu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gt2tqozvmrd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gt2kqwhulsx.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gt2xvgxnmpu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gt2ftnlpwcq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2fujesotn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gt2uirpuylf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2syjfxegi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2ziwhsmnh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gt2fbqfvqvv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2sfpflgcz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fzhhl.top/Article/details/gt2aklevyit.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gt2hwqiaica.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlpsvwth.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ojwcoxmc.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gt2hvgtzano.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2auvbumdz.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gt2kocbqgbp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gt2rlpseeuk.html


<!-- 参考信息 -->