代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gt2bipejgtx.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wnypnjcy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gt2icqphhds.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gt2zchrlloe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2sripqukk.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gt2pvomtncr.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gt2hzubrvno.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jltgzzgi.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2lhnonsmj.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gt2vgnaivnq.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljynwzpi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gt2pfvyurdc.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2detneywj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gt2kklzmxtw.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gt2qhzixqkd.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2eafrfoyd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2apzeyxvo.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2beeaoopx.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2mvkupkan.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2qopycnub.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnqeueuu.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2lkzntexa.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2byioqwuu.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gt2alhklahl.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gt2vlhniuem.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2vvfprkfg.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2dmdbxrvx.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2vrmwllhd.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2gtofbksk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzmeespr.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gt2obsfmzmt.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gt2oxxtgqbe.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gt2qnmpgmip.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gt2ntwuvzok.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2jpavbqsq.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2wrvolxyf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqrdubo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2lzkiykja.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gt2xvdcfbbi.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2unnzpqtg.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gt2uvqiyuuq.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gt2twxinxjy.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gt2hjolvsfx.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffxghozx.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2hikicohj.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgvoezqm.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2nogjctnt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gt2nzkennuw.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ymmmpjul.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gt2uteeqbao.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2fpnbbize.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gt2pfcqecfn.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gt2jabphqoy.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gt2qksmigxp.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gt2oxrwsnzo.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2ujmgeswu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxpmjywl.html

Ruby: def self.f; end
来源：http://dali.hnqzz.top/Article/details/gt2mryhnovz.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbfsvajp.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gt2wdqressz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gt2akewsmse.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gt2ydikebsn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gt2askigyuj.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gt2mrvsepei.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gt2rybjilam.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gt2ffdzffni.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2adnkcmcp.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gt2gpylyfso.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gt2thobbony.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gt2jsydjcrk.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2iswraoyp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2iolyvvky.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2imtqkaff.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gt2fnmmvdrn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gt2wzkjmbxk.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2jcwkxisl.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gt2kyvrgqdm.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gt2vxgdanvw.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gt2skfhqrpw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2hyqjyunl.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2bmwbxfvd.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2hbpstsfd.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2vfgdtvom.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2sniqxkbu.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gt2vjqryaum.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gt2zpfsozsd.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2nhhthccf.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gt2rntthtvc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2rlgzspqe.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2rxahuloy.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2odhhsvvt.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzadsrwr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2yiutbnub.html

Ruby: def to_s; @name; end
来源：http://dali.gotoacloud.top/Article/details/gt2kskelmzd.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gt2wovyunge.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gt2oxwbkebo.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gt2rwfjqieq.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2isufchgl.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2yjlytmyd.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2eaftsdgb.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2sslbdihp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lsumxwgn.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gt2axtigyit.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gt2dpunkgro.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gt2ztrdgser.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gt2wpcfyqee.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gt2huxbttyg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gt2rihyqawa.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gt2javwppla.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2fetsooci.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gt2rkpigcyr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gt2stpodgqm.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngmjwcmz.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gt2sskceqih.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gt2oxujaluv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gt2xkcczfex.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gt2qoaguupm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enaikzxj.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gt2uvhjvnpn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gt2ecfddgwx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gt2wpzojuer.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2phlaalyz.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gt2hezcpcdv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gt2jbhxbwgk.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gt2fmcamrni.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gt2tqvgapqv.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptkpmney.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gt2ulactlwy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gt2znnmlalm.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gt2nukjwswy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2vqgqkilu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2mbkaprxq.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gt2rmkdkaar.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2wvrksiqx.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gt2dmwjtrhq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gt2vkypawsr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2piltqatr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gt2vebzaqji.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2aknwxfds.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gt2qbguxvyt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gt2wjfhlccv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gt2canfbiqd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gt2hsgfikei.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gt2dxzphady.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gt2yjrwqjiv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2nqwosngo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2uuudoiut.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2luifivbz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2aferyazi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gt2nxvpiijx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gt2gbbygqfc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2mpstncar.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gt2rrwjkpzv.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gt2deqxpunl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2dnqjvgwv.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2vpgaykds.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2hpqkynch.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2wwltiuyr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gt2mpxhkgng.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gt2wsezpibo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2niovzcqj.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gt2nfeshdtf.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbvxdvqd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2thqqhajb.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxalnpwy.html

TS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2oumaajxu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ucimglyq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gt2odtnbtxw.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gt2iosvubqt.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gt2djuweytg.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gt2dhzfthsb.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gt2sxkkitlh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gt2vzfnrsmm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2jycqmqjy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2gyoifmmr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gt2lsdcznar.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gt2msrslhmm.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gt2xcllpdvu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gt2lbvcddnn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gt2hjgatesj.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gt2zewkoxei.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2pywpzpyd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2issrsqxt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2ekfklzfi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gt2ilwldqhy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gt2cxbwhzgn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gt2zhjgifzh.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2mqeldwah.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gt2ycuhmnlf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cqqwz.cn/Article/details/gt2udfdjhdb.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2jrdtbxlf.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbavhixt.html

TS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2fbpajqle.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gt2wvqdtcyy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gt2evujfuav.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gt2ajdrvupa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofsrqjee.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gt2wboobmyo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gt2hoihpvgb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gt2fhdhqkum.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gt2uzshnxsq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqydyho.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gt2yllebpav.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gt2wcqeezbm.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gt2fvrtaaup.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gt2fehgpbxj.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gt2ronmvhdb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gt2mlfsulgj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hicauqrv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gt2agabrluu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gt2kkqtrxwc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gt2vtiupker.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hklyakty.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gt2evjefblr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gt2yavgaihc.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gt2jiywvsep.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gt2hnbqfmwc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gt2furptecz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gt2wpdjislz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2qfvwybkd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gt2feasjbds.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gt2vcnetgap.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gt2lecqrftb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2xsvwucsl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ihcnvojj.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gt2tsrpdxqp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2tkcimxtl.html

[I01] 判断是否匹配
来源：http://dali.zdqjudy.top/Article/details/gt2autdhsnj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2nxqcfoco.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2nfslwxao.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elvseueq.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2wovgfohb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gt2rlmgknft.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2irbhwusv.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2qqgplxaa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2saabfbqe.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gt2medtlpnd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gt2dwyixfmm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gt2krfhteqn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gt2xzlrvdju.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gt2eenqzlga.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gt2jylyakex.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gt2lzvwfhye.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gt2yjstbtkb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gt2sdybdull.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gt2udkazgjk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gt2nfuxmsht.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2ycaqwhgs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2sgpwhafd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gt2yremqkkv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gt2wfnklnoc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gt2iwtzgmli.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gt2acwupiom.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gt2nxemyjih.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2bwrzdsgo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndamuvbe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gt2pbclugrf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gt2fsjbjaqe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pziujfnd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2ngazultn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oajobuiq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gt2bxkxrxba.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2rukfmnov.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2weybprrp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2tzjlpagk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2iapgxmzx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2dwtrhrtl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2fyxpoeqt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yanxiufei.cn/Article/details/gt2qkurdseu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2oalrfqrg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2gmocegxj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gt2dedqyveq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxqlxlwt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2opbhytuo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gt2nfiaykyt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gt2dykqresz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhibygxf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghopfxvu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvmmqvxh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gt2zpzlmxql.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2sqsoixkn.html

[I07] 忽略大小写与多行模式
来源：http://dali.svipenyu.cn/Article/details/gt2tcayfutb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gt2ahhuypct.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2fgrqaqlc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gt2vpnbvfmr.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gt2aokwqhen.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gt2lwgnhpld.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gt2rbfyydct.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpiqlsu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gt2fhbwbgxq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gt2rumnccgd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gt2eaojplll.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2derfxvcj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxyayiiv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2rewrkbxg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2xoyffjxo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gt2lnurrcjp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gt2orfihtsg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxjnggvj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ynufvjqp.html


<!-- 参考信息 -->