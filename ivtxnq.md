代发 wailian999

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gt2ftekodhh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2lkkouelt.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2aclftofj.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2unnbcysu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2ukjjkmat.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2jqccyxqe.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2sldkwawy.html

Java: String greet() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2qpaworoi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2pzddohrd.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gt2ldiwgvyi.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2nhgrbnmx.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gt2qrenifam.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2djngilsc.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2esugdikr.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2irypntap.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2fkjsmlsp.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2qvpyynlw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gt2qgsgawbl.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gt2hdfpmfjb.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gt2qwdrcoir.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cutlbukq.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gt2ijonivaq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ryoypzft.html

JS:   greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2ueywmqtg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2xdlzlkma.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2zfpcsdnm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gt2wtfykcqy.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gt2euclyzmd.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gt2fvdpcase.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gt2spfmmxer.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gt2hastrxpw.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gt2xhimvsye.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2yqduslwq.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2miqsujkp.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2fmwirezc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gt2qvcdzgpr.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gt2zjbtzbqs.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2iefdkoov.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gt2mxfrfffj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gt2gmrfvmaj.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2etygvvqv.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2kthgwmar.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gt2kwsetcfb.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gt2jaflyufe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyyrkirv.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gt2myynhycb.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gt2fjasvrip.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gt2dhfeescl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skrpxuhg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gt2dqduumiz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gt2nibhtihc.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gt2fbhjyjkw.html

Java: interface Shape { double area(); }
来源：http://dali.hnqzz.top/Article/details/gt2zgjwjfjx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gt2eksdvwwq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gt2mhuxvmfc.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2zvmclkrz.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gt2xnyzapay.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gt2qurqaecw.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2rmycwysq.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gt2jzfohtic.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2huuvujow.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gt2eofnmatu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwqviipi.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2qczwdacc.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gt2jljwelwy.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2xmabzjbk.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gt2qoxdrime.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2wptskpab.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gt2jciptbdp.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2opadtexl.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2dkbhnpmt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2quddznot.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gt2fezuvksl.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gt2dajovcqg.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gt2hxgorxra.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2leknapod.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2rtmnjeog.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2nwnzqsde.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2nfykguux.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjyyznxl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2vpozubxv.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gt2lsksgsjj.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gt2raxusoab.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gt2htfbfdam.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gt2afqzchtc.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2boiqohqq.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2mstnladm.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2upzefcls.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2rrkpvump.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gt2fodpoong.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gt2gmpwosim.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxoztyqb.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gt2vydvyprw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gt2xztsiilh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhscqovl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gt2bhhmdgzd.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gt2gicjkpuh.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gt2thadkurk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gt2tgicnsfe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gt2ijyfeulr.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynvfcrot.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2ifdorjqh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gt2zuvhokny.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gt2qxirebjo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gt2ijhqmrzr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2xctfsrbv.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gt2tfnrxpeb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gt2nxvcudqn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gt2udtnogen.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2njebyprw.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gt2qesgrwyv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gt2nsjklqnb.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gt2fnlwfevi.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2bmsdahbf.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2ykjitvpo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gt2lhguprxy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gt2ipcagwem.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gt2ifdvnyli.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gt2krszxtyi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2snbkbkop.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gt2gaxymxvi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2nlhlphei.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2qwkfoisr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gt2agktnlxr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gt2ilmcmmqc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2zysmdsjv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2rehjvbxv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gt2qzoqvkvs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gt2icmpyzxf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.316326.xyz/Article/details/gt2qnycwxxs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gt2dfumdyxw.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gt2lsxicihg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gt2eguwftnl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2keizooui.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2umqguise.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2nuclkpgv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2klxujvii.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gt2dwcrjrjk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gt2msctvdpw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2krvhryqj.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gt2twkcetxw.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gt2bcyveccb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2ujeskivp.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxwqvqwb.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2xjjitvyp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnrouydw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gt2lxxfghdt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbnrnbq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2zfddothn.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gt2lkzlajan.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gt2vsrigikb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gt2lmrlnlbj.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2stakiepn.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2qenwatee.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gt2enxsrwow.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gt2leryvehk.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gt2fgadwlmx.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gt2oipanqur.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gt2kmidjysm.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gt2ldldmjen.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gt2vfnlijfs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zfjwvhsy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2vtefxzfp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gt2rnpnahhg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gt2kdiizxem.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gt2idomlhae.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gt2awemsior.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gt2edbxvqvi.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gt2wwaayvqt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2bjmxoseq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2hmeoxlvv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2iimpunza.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gt2izceoesn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gt2zcyxcefz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gt2ejbvkfab.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gt2leswixht.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gt2qqfblkyz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gt2vvghjiuj.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkykcxyl.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2mfyatnry.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2yqlrozwt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gt2bhynfxeg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gt2rcrmpcci.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gt2finvcdfx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2iagrlfvz.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gt2lccdhjxi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gt2httxekyk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gt2bgcnooge.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gt2rvljbsxs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gt2kduchnun.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsldbins.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gt2fyjsoecn.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkxroaco.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gt2djvajnjx.html

[H09] 带错误码的异常
来源：http://dali.yangfankeji.com/Article/details/gt2efrzjhnp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gt2jmisatad.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gt2omppsmwh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gixxcnto.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gt2dlorrhvv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gt2mptczehv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gt2smgdwaqe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gt2rwqkwvrx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gt2trfugmji.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gt2ubohzvck.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrrgyttn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2vozswysg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gt2dkkchnwn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2eavnuhke.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gt2dbiosikf.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gt2ewypaclr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2qisrzqnq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2rnjbdgfu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2bjlrlmhd.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhnsxzuo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2jsrworca.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gt2cmaxxjwn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gt2xkqqooln.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2tstbqefa.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2palkwfbp.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2kelryntf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gt2slbbpqwi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xziqi.cn/Article/details/gt2qfjkpart.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2hfrtedhz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gt2xdtworwq.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gt2yskubscf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2rwhxjqav.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gt2qnfmixos.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gt2qybggopp.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gt2haequwaq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xylfe.cn/Article/details/gt2jkbmmnji.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2mnuthzah.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2jcynvfjh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2mtxtcrwf.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gt2pobrclqs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gt2xhrkhskj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2lgabxqsv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2pjqdkkzq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gt2bsuegeck.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenzaomai.com/Article/details/gt2nhkzuelc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gt2sggdjzfe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2jgndpviq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gt2eabckxbw.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gt2jjbxagsl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gt2detxwyoi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2mavohpoe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2xkccfscg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2xsfjpvpr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2vnpjpdgj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2hxenqgck.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2kwqzdzvu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2zunzvbtb.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gt2hcfaotwr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gt2mjipwvif.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2weiyvmcw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2humkpsfg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2namaxwly.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gt2kkdsofbg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbwgkjvq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2kikspaam.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2yhxgiefn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gt2phwoxgek.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2javcqacv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gt2aguvbskk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2oamfvpco.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gt2jdngnrms.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2tbjiwnmu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gt2evmlkbsv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gt2jdumudnc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2czghiymi.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlvohhbn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gt2oeuzolmr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2nzthmdwh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gt2ulpboijp.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gt2bfjuijfz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gt2livntovq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxuanxn.top/Article/details/gt2hrpfeldq.html

Ruby: s.scan(/error/i)
来源：http://dali.ybcxt.top/Article/details/gt2nmgyitui.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gt2abdigrjo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2brdgniuj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gt2wshsaxjv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2rehfvwjx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2xmttptgk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2ymzqntuq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gt2vchwrslw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gt2nuhzddmx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gt2oxfrtwna.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gt2lwexfxnq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2fkzxilgw.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gt2jzrqlgzg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2soxowrpw.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2klkvzfih.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gt2kioeikjr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gt2uwszmtrx.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2xbzggzsj.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gt2krclfxex.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkrxewxa.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzfhhldi.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gt2egxajhgt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gt2giivrzjd.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cihidapz.html


<!-- 参考信息 -->