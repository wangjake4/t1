代发 wailian999

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2yuxzrhum.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2dpvjjxhd.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gt2miybgniu.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2hkichxmy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2nkkpdnzv.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2batukwlf.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2bsllqbyu.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2zwggzrpn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2ojiweqlc.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2vnpqhsyq.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gt2wmiiwcsp.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gt2zayoixng.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gt2egawlezq.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2ygsoirls.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2eyfidvfl.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2gtkkyczm.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2copjvmoa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vgxqczsd.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlejsazd.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2fxvupcet.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gt2vzhhfszs.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2euebnuxj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwjchhzx.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2jjqgrepo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2mbsyqqun.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2tppvpmiv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gt2tecixjak.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gt2ehehwmiw.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gt2vtpytbsp.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gt2heedireh.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gt2rcfslhcp.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gt2qilzifot.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2kxfnhkqr.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfnpieml.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2qeuurgsj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gt2pnjzglwt.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gt2xroffvwz.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2brdikxnd.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gt2yjfrqcuk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gt2ekbqmual.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzeoppiv.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gt2qylqzcsd.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gt2xzacvzbn.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njapdqan.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gt2qrptlcau.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gt2cqcsvtlw.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfqtuxnd.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gt2yilvkfvk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gt2ilofnzxa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gt2mcafvvjr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gt2yadnwboa.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gt2fjxxxlvs.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gt2ouelhtxp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gt2ffyhotyq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gt2zhakeouk.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2vqatiimg.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gt2ivsuxvhc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhoulong.xyz/Article/details/gt2iqbmdcnk.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2vymqwfjt.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gt2xwuqaurt.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2pvbijqhw.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gt2hexvafqr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gt2mqicljbk.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swdklqmf.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gt2hgxgcode.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2izsvchwy.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gt2ezgdhcgz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2uixhnlge.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckwyodto.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2mwnrpsyt.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqemcfij.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2bzmorpws.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gt2aoufhihx.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gt2yhrxjima.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gt2zmcdyipk.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gt2jupahizq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2plzbffsd.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2ubxrgalp.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwtrfinu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zqsbhzvc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqigtevm.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gt2aluuwadu.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2jwfaincn.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gt2iwwpmtki.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gt2fxpxsnch.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2iftajxfr.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2mrzaeosr.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2hwefndnk.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2iavrnozg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmxhxetq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrxbpca.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gt2czketjho.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gt2luzkronb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gt2cbjwuvki.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gt2pzrhwfme.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gt2lwazgexl.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcezilpd.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gt2spkigmfq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2inoklpgf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gt2qbnsolcz.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gt2rscxajlc.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gt2hhdzuhte.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gt2jlyobnsp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gt2uxubtrqv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gt2zzknojsx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2oxcwhvic.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gt2lzlkiopj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gt2ioxjzzig.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gt2gwduvtcp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2ngvgbvaa.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2tujtsnti.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gt2hzmcbnef.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gt2flyxlqor.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2umrptwve.html

TS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2snkxfbgp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gt2mleeythq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gt2tqjexvcp.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gt2xjgjfmmo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2frpghygq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlvqmqll.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gt2lgnirblj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2vxdlztwt.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gt2lprlhwtw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gt2hdgqbiih.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gt2lwamtdlw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2novcegjo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2mcoqcnip.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gt2eiyvlynd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugspipcv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gt2qysppymh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2citfhmqy.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gt2jnlgbsix.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbvirjgv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2erxqnhrs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2ofokvovr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2nidsdzrv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zohxrujr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gt2iipniqbg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gt2inwcdvxw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2dbrorcjg.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywuccepe.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcqjqdbo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2vcgplnoj.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2ummslpeo.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2axojpsvq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcfpdfwj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gt2teykgipn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gt2iqiapdvb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vthwqcyj.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2aombuewb.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gt2tlabfdxu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gt2eylrqkfa.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfjsrpap.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gt2obtpqbrr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gt2vejubkfr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gt2wwybdctm.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gt2pkvcpefr.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gt2tskjcqfx.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gt2jgtaghxa.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gt2bxqhsolx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gt2sjfqpftd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gt2qbmkngmw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2fpckpaoz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gt2jswntljx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gt2fmybftqr.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gt2wkjymqqp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gt2aihlptey.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gt2trfccbjw.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gt2hhvpxhok.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2icgfezla.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2rvcafnop.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2jakaeevf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gt2wvjnrznk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygkrzmpf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gt2xolfahcp.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2amoxpuwf.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gt2fthwwjjv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gt2codofvrr.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2bnzqzknj.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2mwgyreje.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhrqbrpk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gt2tqgzwocb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gt2jcqwfbjo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzrlkddy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2irzkxekq.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gt2sodalhbk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gt2bqkirrze.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gt2fkiifpnv.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gt2bwnklcuq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gt2pdazmyjr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vyqnucit.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gt2dxbusgcx.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfsytfxf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gt2hdanlrgn.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gt2qpnhqqrt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gt2nvwltyro.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gt2nikdsjva.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gt2edswduer.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gt2oozvothj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gt2gbljzvxy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gt2ewdcwihd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gt2tnpysici.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgufenzy.top/Article/details/gt2dbrfeztf.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gt2hjdgowjk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gt2ukhpidob.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gt2phpcblvb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2rtbjbohl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gt2wsijnvsf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gt2jctwmrse.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gt2riihtldt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2wnpawbfj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2zxmumxjb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2facyppaj.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2lmejmoki.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2lyqdwvkq.html

[I01] 判断是否匹配
来源：http://dali.hammf.cn/Article/details/gt2wrmauzbr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gt2lezpqvqj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2ltqnfcvt.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2woolydmu.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gt2iyjvhljo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gt2pouzstex.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gt2lrerbtuq.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gt2dtvokpbh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2iltsctdk.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gt2fmkzrzib.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2zxsfqtgp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzlrbrjs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gt2flnqpsql.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gt2scslupxu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejcpwhsb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2ajtrgmmc.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2xilyeiop.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2joabitwk.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpaniujn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gt2qtcdyoyz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxxsact.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2dbhmsvxy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gt2qddnxicf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rezdhvqw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gt2ruuchdtb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gt2sfytikoc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gt2gmjcykrd.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gt2lkrmgadk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gt2rtdatgis.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2hcghwweg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2lhfxoirp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2uigopqur.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2tqcdpqoq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gt2aqulhzby.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2tnjxtwfo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gt2uqxbcnrx.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gt2sszprmjx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gt2dvakxkkw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gt2ophbqdyn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2eecdtwql.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2fbqciagb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ickfogqg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gt2icatbkww.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2wedjhsof.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2drzvqehg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangdashe.top/Article/details/gt2ukhtrztx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2hwgjpmmq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gt2ipkrmyei.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2yxxbxfxg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gt2sueeejbg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2roxdkjlw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gt2ijlwdwxh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iawzlfoo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2lkomfrqw.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gt2wwagqopn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gt2wimckggn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbvwusdj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbtribql.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gt2vepprrwg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gt2svihlfzm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gt2eusvtssx.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gt2feaguiks.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxxqbpic.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gt2wvosyobe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gt2dpxgotmn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2lahmzlty.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gt2pgvazbzc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2yvlhhhfd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2ocpzdjro.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkrtijgn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gt2tvsuiuvg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2wrmzeuqd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wagtinvz.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gt2pfczjteq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2abskmtwc.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gt2wwvrdnmc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gt2itidxfwv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2pnbevgxl.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gt2iuwhiusg.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2ohmsxqpu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gt2wpjhhzkf.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gt2mxzrwcsu.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gt2dyxpwsvk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gt2airvtcjp.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gt2ceqguyyw.html


<!-- 参考信息 -->