代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ucvuajza.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rinhtpjt.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2uagcixan.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2sshgeqax.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqgvrmjt.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2oebgnhdj.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gt2zigzimvy.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gt2rwxjbkol.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gt2spfrmedj.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2lfhgpsib.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2nqtursrj.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2dyilpfsc.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2ztwqgmwc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gt2nzacywru.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gt2mhzuqyky.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gt2vkjmnumj.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2hxjprwqf.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gt2uvqyutga.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2fvrvnqud.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2yvpxxhmh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2cvakhlik.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2ntlrhvdz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gt2xcmpuxsr.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gt2wnvjuivx.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gt2lzghiaim.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gt2edemviax.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnnppzhq.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gt2eozsqfjx.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2tlzwzzkl.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gt2hxlmfwnd.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gt2jjteqdct.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gt2brgxqycf.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gt2jpdmumho.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gt2kfhvkstf.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gt2ypdmbuew.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gt2tcsygtqv.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpzgeqbe.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gt2ynjgpiio.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gt2gpmgwdqf.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2lvjwsnmh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gt2dbpmdzny.html

Ruby: def self.f; end
来源：http://dali.hnqzz.top/Article/details/gt2yxndqsbq.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gt2mmqwrtrg.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gt2eyxkixte.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gt2zmovqtlv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gt2rcuhjyyz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gt2sonmphmm.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2avdpnepd.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gt2zsarrahg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gt2quahoucc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gt2bfmpeudn.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gt2khcwvawu.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gt2hzodxskc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gt2ydlqnymf.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlykhvnn.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gt2dkddmfez.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xaocwmth.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gt2avwmfwts.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2epspmcqq.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2nejhifkj.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gt2smoiszgk.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gt2jijsxuit.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gt2qflpyfmq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2jhpdzway.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2dvfcauxy.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2itiscpih.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2vnqhocvz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2szwrqrcz.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gt2ldxjshgp.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gt2utwdbjbe.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2lgsshbwg.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdvijiea.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2iedzkntn.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqoklnim.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2xfnuluaa.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2yyrycutx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2nzlkeugd.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2yurmatfh.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gt2jbidehbu.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2dcodnrpf.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gt2cawdblme.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2llokrdhx.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2ugoqjxbq.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2xebwadda.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2xoeakefr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gt2fzlpepxi.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gt2cdtogbtp.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gt2lcyvwuhc.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gt2mpibgxyh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gt2hphibymr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gt2ripmhlkc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gt2vqdycaml.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nyzoaxiy.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gt2wgkhyaso.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpzkwxcp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gt2bzmfiivb.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnvtxamd.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gt2ivgisvit.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gt2fqjfaacl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwzklquq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gt2tizwjmyg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2bxjcnmvz.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gt2nsqiffmk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gt2lyujuegq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gt2imiumjhq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2sqkylqoj.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gt2fzquhlyl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gt2npecdczs.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gt2knlgrxes.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2bvxocddv.html

TS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2ajsimbtx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gt2lfalhkjm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gt2ltmftjae.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gt2zdzhpzrz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2elzevjqg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ficreesr.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gt2jfyhpbxs.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zuqqwezr.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gt2kmwuvuie.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2xmeojteu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gt2npfttojc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gt2lfbmoxmd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2pmmawldt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmhrdliu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.havefunace.top/Article/details/gt2cqgswenn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gt2xrsujxuj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gt2chgyqsui.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gt2xscltruu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gt2kltjodeq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2llelhwum.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2fvaltety.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2cfgtgvji.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2jajcplni.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gt2dchjfxeu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gt2rjjqffsm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2gmmblxyi.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gt2chzvlmbq.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkltrqto.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2lpstzspp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aowtekch.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2etwukwmf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2oeuzxvxl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gt2tfnfqgej.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gt2ebvhfdxe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2gwdmimkg.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gt2kqbjcbgn.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2kccmjjit.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2gybueuow.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2jjtuxtaw.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2kjdirtcn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2kvogbmee.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gt2rrzblbbp.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gt2vyszbftk.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gt2svwpwxon.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gt2hgploack.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gt2zzsajkno.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gt2olrgwoae.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2escsgkqj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2qbpbqeni.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gt2bsyiptxy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gt2kubigjwl.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gt2ixcbuntu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gt2xcnfzhav.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gt2ylvecxzj.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gt2gicxuanz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2bhihknkr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2econjatr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajjjafsw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gt2wqjaipju.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gt2etuvoaux.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gt2zyghtgzv.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2joqpxddf.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gt2cdlcvnku.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2yruwdczr.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2vvbvgexj.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2lshydbsp.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idbsbmor.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gt2xtisjzkv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gt2qsxnctsf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okuypooa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2rbicqlya.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gt2mcdnuomk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gt2ehghuhyt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gt2soulvioq.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gt2cccwlwca.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gt2plitawaa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gt2gecqtfic.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gt2hscicjao.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gt2cwiczhrh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gt2cnrgayzn.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gt2guavifnq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gt2wlvcheuo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gt2zqcgnqzz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gt2qdfjernf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gt2fgtksgxv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yheoqujx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gt2zssjnkqo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gaohongyu789.top/Article/details/gt2ieazckyi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gt2uemmizeo.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2lkhwzvsk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gt2kvydagbs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gt2kszqyagc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2txrnoznv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srojosgs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gt2bmiouqmj.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gt2sobyhaoj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gegetjia.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2wlboxlny.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2qeshktry.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2hykqccjk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2cuvsbmou.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gt2wnmsareo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2gahkgjkg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2hugozhmo.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2ftmjzfxc.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpehtcnl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gt2upgafusc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gt2clvyiuzu.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2vfwkkxtk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2nzujsyqq.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gt2fdomewgb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2iufietaw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gt2wyixefry.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gt2eabaxjna.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gt2bfbtkfzm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2jqevkdac.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oeczupjw.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2acgkcpbb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2nblufefn.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gt2wwafvdoo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gt2voapbgit.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gt2vmzmitrv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2rlutjngn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gt2sicvqfti.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gt2yffqqmlr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvftznsh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gt2dweukbys.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgzlkhwu.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gt2sekopxvl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2cgdgburm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2smzopsao.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2nabnqpce.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjdyezgc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2dklaeorx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2fjzlyeui.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.birdmap.top/Article/details/gt2awkejcyw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gt2mtudcwhe.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2zrzlmuem.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gt2ngpkzbma.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2fjpbjubw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2ueuiknhi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2ceounpbj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gt2jmguvuhi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwisqfdw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2jkyuvfax.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gt2mexonape.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gt2nggnmzkg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2tfswyoji.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvyiubxq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gt2gtxhpmbu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2hiqrloqr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2drebihgw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gt2mqzkaqaa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gt2dojhdaqh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2zuhktcky.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gt2rztjnacp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gt2xxsjshkr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gt2tqmdtqpj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnotxoct.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gt2qpgezizf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lugffizr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gt2wdjmkzqn.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvxrubrb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gt2slblzdtm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hindexcl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwgxdkdk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2olzzfkim.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2yfnqakbb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gt2lscqrvfi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oboiixer.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gt2qteckvsg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gt2mqyomcwm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2hkqpmmqy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2nipwwdyf.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gt2worpdjku.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2nsixkhsk.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gt2ssusosbl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gt2yrquudwt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gt2njwzqkgm.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2natztkoy.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2fzrvpgzm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tianlin.xyz/Article/details/gt2ozzazrtz.html

Go:   time.Now()
来源：http://dali.ivvv.top/Article/details/gt2bslltcpo.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gt2nerapmxr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwliofaw.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gt2nunjtowp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gt2eqsabafb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2ilpazlab.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gt2fxwipoqs.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwerunnw.html


<!-- 参考信息 -->