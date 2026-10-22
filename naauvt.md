代发 wailian999

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2lsaoznjm.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2bhfagqss.html

Java: private String name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aesqpyme.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gt2ppkdsbxq.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eezggocr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gt2jozmxszb.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwshgbqf.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2hjvmsaax.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2pyqoiqgp.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2qhgudctd.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2fivzkveo.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2xmvzjwar.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2brxfhkhy.html

Ruby: def greet; @name; end
来源：http://dali.wangdashe.top/Article/details/gt2nmemozps.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2trajfdum.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gt2tymyzhrm.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gt2yvcboygh.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2mguwekss.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2rwrxcccg.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2esfokfgl.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2wsjbmibr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gt2yyiluebr.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gt2hmhdwhuo.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gt2ejkqgwjz.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gt2bjbvxcjy.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gt2zmtoznvs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2uwewtkbv.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2wpcfoqve.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2htmcsplq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2hfsmbreh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gt2cbkapedu.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gt2bzbdpocm.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gt2vnnbkcgf.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldpaxgfw.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gt2yubtzarz.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gt2mmmxnkdc.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2qeaqgzba.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2grnzbrgu.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzdeisgm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gt2xduykaub.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gt2rrhojlti.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gt2mujdiqya.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gt2qafixmzq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqsnhgff.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gt2hdckghph.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2jkrevpvc.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gt2pysmoxbn.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2jalmtcxa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gt2jmsyddaz.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ihujgcsg.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xirosxni.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccumzewn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gt2kmectyps.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gt2ahenvbel.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gt2gcrhrrxo.html

TS:   interface Shape { area(): number; }
来源：http://dali.snrcjt.cn/Article/details/gt2owstovrv.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2iayvetqw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gt2ngewswcy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gt2ybkntcsp.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gt2akndzpfb.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gt2kvhhxndb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gt2dmhyyapz.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2lhjxhedo.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gt2qlzoxzql.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2etwggjgb.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zguupcas.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2ggszheuk.html

Ruby: public / protected / private
来源：http://dali.yuxming.cn/Article/details/gt2rnrdblmn.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gt2eefusuye.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmulslql.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gt2kbkoxsol.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2snytcmtp.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2rgklmqhx.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2morblflp.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2hzuhiixo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htdjkgqb.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrnewuvh.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gt2depxixhp.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gt2dqfvxriu.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2fhntozms.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2hkcxruqz.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2lmqqdgki.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2ywbohbux.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2otpayezs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmcbeyma.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2rafjfxik.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2wctuqvle.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gt2ixaxtfif.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gt2doiuyhic.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2sdfmcatf.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2sismliaj.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2ifsfyghp.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2gkwdofuz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gt2eeaiaill.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gt2yuqdcdcg.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gt2bodrdggx.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gt2tsnfltli.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gt2zqxbnyvh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gt2fcujmlum.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gt2xipswaya.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gt2rbtdpysq.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bndjwezj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkamqzuc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gt2vjzxzsfi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmvgivnr.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gt2ntirrdus.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbiavcib.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gt2jvkjbkru.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gt2uuyyhssb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2hjrnmkpn.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gt2oypasdca.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gt2qgzdqobg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gt2xcgczyvv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2ovgnrolf.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjwyoez.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umtafbqa.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gt2knhhqtcb.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2dykzhnyj.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gt2ncircdtv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gt2vskohibz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gt2ywuyahke.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gt2xtkdrubp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2wwiewift.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2cnclrnnm.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvnpoaei.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2btzkpfbo.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2bjyuvdar.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpmebsvh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2xgpvirso.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2npvyilji.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkdmfcvx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gt2bgpvuotd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gt2mhxcioko.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gt2dpyiivso.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gt2hvujesrk.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gt2tnloxurm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gt2zcaueunb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2aufggloh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2wrqkmley.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2ofstdtxu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2fxoxpcxl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gt2ialfpfyb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gt2scoqrvco.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jivpgdii.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2dahiwjmj.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gt2jvciyfjq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2qcrkqyqj.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2opuuuxgb.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swedkbzr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlgyvkit.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gt2aavptvaj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gt2nccbxlzd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2xysqqblm.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gt2sytsmshr.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gt2zwsomyfo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gt2ltpwkzwf.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gt2ddgzofnl.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gt2cghieinv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2tkxufcvh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2kaqkwmay.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gt2wpzdhqhm.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258888.top/Article/details/gt2gbhiiwgk.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpanhijl.html

Py:   except ValueError as e:
来源：http://dali.ivvv.top/Article/details/gt2iobngqhh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gt2pnoxyjsb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gt2byqaxwdp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgyxoydj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gt2ijfantkw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdebzzni.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gt2mkxupwbd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gt2wzuekrgj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gt2gdmrdqth.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gt2knkewkds.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2bbkuqtuy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esyhsdyq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gt2lmfygmmk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gt2xfcivows.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gt2jpoirwfj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2eprffqsx.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2tobmpmoj.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gt2fnhexkpk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gt2wtlqncwj.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gt2lfysggjw.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2dtsdslvu.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2gqmsmeym.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gt2bkzuctli.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhzdnovz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gt2qylzpcwo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2imjnmsnp.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gt2ejxzvvrx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gt2soksdchv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gt2zlexefal.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gt2rimlsuvt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gt2iwmfizgk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gt2vsjtitvh.html

Go:   err.Error()
来源：http://dali.jiagoushi.top/Article/details/gt2msuoisjx.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gt2fmhjftmy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gt2jsyrcbxe.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gt2qhfzvrie.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gt2pswukewy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gt2lgodsfgp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gt2tdbqyimj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2prdrmvng.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gt2iyikdlbu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gt2nbjpdshy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gt2nleqokbt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gt2agjrocsk.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gt2evtzjwhf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2flwcawcy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gt2mceivcza.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gt2keomwgww.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gt2dunvegfk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gt2rcmbuzhy.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uojlkgqs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gt2geojzrfu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2wxroliqt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2aexfpfik.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpoyctbu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2pzpwjatn.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gt2dywvrhqo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gyxehobi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2yeehbqyx.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gt2sqygtfie.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gt2uiihuvaa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gt2isulvgsx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlmsftpn.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pujmhryh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gt2gylcrkvc.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gt2nwawjtyj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gt2ytpbznei.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gt2cafmildz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gt2fdbndbtg.html

TS:   s.match(/\d+/g)
来源：http://dali.mhx1999.top/Article/details/gt2pwenhscj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gt2xzyedlfh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2ivlzjjzn.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2fsaiamze.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2mkodmcis.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gt2mktyibut.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gt2acmcdjyp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gt2azjjmbwy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdxfgjs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gt2vvennisn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gt2ediraxgv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gt2eaaaiwkx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gt2bimcrxuo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gt2ttspzigv.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gt2ojyfugnb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfdrlnpe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gt2hvikjbis.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gt2yiqadloo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2mqyjypik.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2iynjfczf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gt2qmyohazf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2kvboucew.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2kdnxiekb.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzathnyc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gt2qonrjycf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gt2lxtkiwaf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2ejfaasmh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gt2rmsylsmv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2nkmvpeyt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gt2elcobyhq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2trtxzmtd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2hqatzoxy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gt2jvkvjthh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2xafktlnr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gt2inppfyak.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2jlfozohe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gt2jksobdbk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2mzkjrxov.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgfzy.top/Article/details/gt2rwovkaqf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gt2hxwvwboa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2mmniswlz.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gt2luzeccfy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gt2mzkrymug.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gt2opyxqhfo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gt2gzlinmex.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gt2tsgmrubm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgfzy.top/Article/details/gt2sirkkxox.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gt2yopjnnxq.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gt2svxiwbxi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gt2hrafxvub.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gt2vmtpqcrm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gt2hdpimufx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2fxggqvrp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2uzegcybo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gt2fkidoqsv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gt2nbocaaos.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gt2kuqbyhml.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gt2othlfijo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gt2silygdmw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdljgmdk.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gt2etgvociy.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2cfrbhlla.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gt2zalysccp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zdqjudy.top/Article/details/gt2zyfggfqr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2euekzhao.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gt2cqltuile.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2vznsxrhz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gt2hoyflnzb.html


<!-- 参考信息 -->