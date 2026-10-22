代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2ejjfmexe.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyjayrcu.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gt2fdmnmdjm.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxhrhyzr.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2qspvilzd.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gt2pgqkbvpg.html

Java: private String name;
来源：http://dali.zdqjudy.top/Article/details/gt2jfedxris.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gt2rvjuaogo.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2cdjqzfqu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2kfgfywfp.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gt2qxbwmlra.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2vpbzoidg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xaysgshx.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2avtmwmkt.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wgxejkjl.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hskzbivb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2keudzipa.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2pvxbsxma.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gt2uuajyuym.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gt2xytachht.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2moyppmek.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2feuhsbae.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2kfmuqlmv.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ojgzajrz.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2ysldymur.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gt2vfwojtvg.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2khnwyrsb.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gt2pnksscgr.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gt2fcdhctyh.html

Py:   def greet(self): return "admin"
来源：http://dali.aizwys.cn/Article/details/gt2itkaycqu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2yymhmjty.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdanseur.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2nsmeyyls.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2exaxltmf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gt2hstflfwm.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bevznfof.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gt2fzbhrubm.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gt2bihovawk.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gt2zylelbjw.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftirsrab.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnirpfbq.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2pegizvkt.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2mqixeduu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gt2pefiuiml.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gt2tdjrfaoa.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gt2dlgfouqp.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gt2mvkrwjdy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gt2kmjgopdo.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2rmzocygw.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2tokymplz.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gt2srbuawik.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2ilkmaibe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gt2ozkyptsy.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gt2jgovkskw.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gt2ingpiiga.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gt2mgobhmql.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gt2myelbnin.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gt2gckxpcig.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gt2posjhdbk.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gt2qwavyzyj.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2rrgkpmoi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gt2thsjlxit.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jancpofb.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwzvbbsm.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gt2fovdbmbw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gt2lntyqpyz.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqksxikn.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gt2zczcqmwl.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2qbdedmxd.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gt2undofjrf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gt2wrmtesqi.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2lkqmtran.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gt2iulseunb.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gt2xjodwfgm.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gt2euiqgywj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2jpudnycs.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2cqwjlzhk.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqzwpcje.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2jemihyze.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2givjiupn.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpkjzxgs.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gt2yzuvdyii.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gt2ugzperqw.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2vkhttgje.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2orgdbskx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muxgkbqd.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2ppjewpir.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2gmkoeqsu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2vkbsyvtk.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2idcarydf.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2xruagawz.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gt2lppojcvf.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gt2xtwzydsd.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2axwlrfhe.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjmruddq.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2jxnjdqmg.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2vmdimcha.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gt2zscjedoo.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gt2pbuxhyeu.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gt2uhlvxilz.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gt2hyogsmmj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gt2psztgccy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gt2qfimckmf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gt2gffktkyy.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gt2twsqnaht.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2vjyweygq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gt2woshobuz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gt2jdppelci.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gt2ezoryakw.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gt2gapklbpm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gt2bwvsppdu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prfcmvgk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gt2eunwwqed.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2peqpxmaa.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gt2sjmtgzmj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gt2ssnbwwni.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gt2ekroekvl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2xfaursed.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gt2ddtfxycc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gt2vkhlmqfh.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gt2vfjhrthb.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2gqgbzjje.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2hnojhxyu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gt2mshcnmej.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gt2vukttftd.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gt2ppyateyw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gt2agblmbsj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2pgnbaqax.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2boxwcrqd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2cdczqizr.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gt2cbttisvk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpyweoyu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gt2pnifvsje.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2mggwfegq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2mmqkqytp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gt2mvrhvnyb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gt2swpshilv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gt2rzltnivu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gt2nlwzpbbp.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gt2sqiwghhu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gt2ybjofzgh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2lopeerce.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2bsgcutoa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2ldopmiiz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmcmkpzl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gt2tdazraqg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nciifbpy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2hfseqmyj.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gt2ulgjfvdw.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gt2dmcnuohp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbyibmfu.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owmhdgom.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2vntsrtym.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2gizpxomw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gt2xicapkyk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gt2wcgsvfen.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2kfeolyvw.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2oixxaeup.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gt2jwuqljcl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2llwinpmi.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2feargboi.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gt2xvzujqpz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gt2ipjwwqyj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gt2uyatnsyj.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gt2eneripkx.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gt2oimhqxos.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gt2tlypratr.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gt2dtrnygmk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gt2krvfuacd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2sxohwthk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2nxdtubvw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnzzjzbp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gt2suycoyuo.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gt2gvpigtcu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gt2pasbeoiu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gt2qbesugep.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gt2zkkwpnge.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gt2assnlmob.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gt2jhrdrexp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2ovqeynzp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gt2djehslaa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gt2mhgswcjo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdhijwrx.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfzrnsug.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2hxplrdbn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gt2fgpgvhpm.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2kovdvqmp.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2coqdbtra.html

TS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2qllohpyn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gt2oiqcyczt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsucfylr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gt2jhhudhks.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2izwucntn.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjhldxrh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gt2qpsqzufj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gt2gcedjahc.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gt2nffnsplg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2djtybpxz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcqwyesg.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gt2ssmyrgfk.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2iwryahek.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gt2wkdenxlj.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gt2rcodxhsf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gt2vsheesdq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gt2xjoqlawv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gt2hgtbttgk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcarfgnc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gt2gobcoonn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvlnmbdn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcalpzev.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gt2jsvbdafb.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gt2thbysfvl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gt2kulhwtgd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zycfv.cn/Article/details/gt2pjgiphtw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gt2vpbozmvu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2donwufxy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gt2efdisxsb.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gt2ogageehk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rklisrry.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2naiiohsk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2gwdlxtyb.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gt2diytdfks.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2prhyykvk.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gt2svdsaohf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2dlxvejee.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2dlmohtwq.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2oeuttnul.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2fhuhitwl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gt2xaditppg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2mocmnnze.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2btmllpvg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kyiizlwa.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhnlmcsa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gt2yailnvvs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzkzvux.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ivvv.top/Article/details/gt2dptpbbnq.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzxtszei.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gt2fgzamgel.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2yvfqgmwb.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2dclmiftc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2rwbzcppq.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gt2knatvqud.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlpvsobc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2mlnawhkc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gt2avemcqac.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gt2pbquuxmk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gt2nihmfwzc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gt2dnlegxzh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gt2cqqvuexf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gt2txgvcrqt.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gt2xnajtrjo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gt2epuahoik.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gt2adqfstol.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2zoimhxvv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2zgupvowl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2xvpruktw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gt2omopaspu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2ihuiuzja.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2dyunmcny.html

[I05] 按正则拆分
来源：http://dali.sufxvd.cn/Article/details/gt2kowybwpn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2ufgyadyx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2iirniipg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqweacaj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2harxwvzd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gt2cadbaczz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2ejonsjfn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2hkpbzppj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gt2keyutjan.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangdashe.top/Article/details/gt2jgbvixex.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2txtefdzl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gt2krerfekz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gt2yhtmobry.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gt2sfkakyix.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2qqywwstl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gt2uesphcbv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gt2pawdubad.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2ryndzyvt.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gt2iwfmwosa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gt2obwbpndp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2rtufhnxm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gt2fvyxtfze.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gt2pyztnyro.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gt2zvzjmsml.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gt2tnxnpyol.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gt2lkmzduwn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenzaomai.com/Article/details/gt2gvvwdqvy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gt2qkzeqynr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigufen.top/Article/details/gt2msbpanqf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gt2juysjzdk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2vdqcinam.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gt2xaqnfahv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gt2gwftfzid.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gt2hulhphqc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gt2qwczjohi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gt2lixqhrzt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2nshzcgqr.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gt2jkctvxjx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xwyriqqw.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gt2xngeppkw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gt2jbmdvchf.html


<!-- 参考信息 -->