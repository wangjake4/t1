代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2ajywgruo.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gt2igrbyvrl.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gt2cwktzolv.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gt2bhmsxegc.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gt2etmxqgea.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2jcpllqva.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2rvselboa.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2ltlelggz.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqynaolk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gt2zfwgqsfo.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gt2nbwlbqvm.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gt2ffyykodi.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gt2zvzwdmfu.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gt2whemzkhx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2agsliunu.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2vhibzedu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2dwxlkbar.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2sdmwevqy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gt2omilrpwi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jgveigel.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gt2aixwjjdu.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2fykfyikd.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gt2gneqdvgv.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gt2sspxtuiw.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2hprqmqwa.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gmonegri.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2jqihbwrh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gt2smtpfydm.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ecplwnok.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gt2qoxmvsru.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gt2putlyytw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gt2vmycrenq.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2afjusjgi.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbcqlxgo.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gt2mfdznwfl.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gt2wsyllqjh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndnyzthd.html

Ruby: def self.f; end
来源：http://dali.hnqzz.top/Article/details/gt2sflvaeoe.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gt2ftahcnbv.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gt2bpxkpeuu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gt2vuisjuqt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gt2kbwdsvpi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gt2pvecpxuh.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gt2vuhcozwn.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gt2ovjehdtb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gt2uzvkxqhl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gt2lgabezsx.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gt2vsdgzgix.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gt2tnrernvt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gt2njinkycj.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2lvttwuud.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gt2brkjfkeo.html

TS:   public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2bsvtonwj.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gt2kmbtuusf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gt2elvubuig.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2sggsximz.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gt2gexmwmmi.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2cojkqdoj.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gt2vusijguz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2uoopuztz.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2qewilgun.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2xzbnthsg.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2alxbgicj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2szwermki.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gt2vsubtlam.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtmgxqpf.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2gomcpxej.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2yhkofsyj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2fmufinto.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2uulsbtgv.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rdmsjprz.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2iznavxgg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2yhdbhfqq.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gt2xvwdobye.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2rskyvhmv.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gt2bzmdfigm.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gt2coconksk.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2ujhgkfim.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2idmcrolb.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2cjvtvjtc.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2mvmorpud.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gt2vgndupoo.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccgymapa.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhnakngd.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gt2yyapvvns.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jggaywrg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gt2gxeasbvk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gt2idomqqgs.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gt2skbqiiac.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gt2hsjptwvd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gt2vpinqccb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gt2ybkddsxe.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gt2wknpbqwn.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gt2dffgpojq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gt2cbuensez.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pluapqpq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gt2cxevkhki.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2wxzgiqxn.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gt2jdzwashm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gt2hhmwvxrx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gt2pofrksrw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2hdmmdejy.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gt2xactxtnn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2necvbgry.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gt2qelcxuce.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2hetjwgtr.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gt2ieqqvuyb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gt2fclwnodv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gt2lgvabbgz.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gt2rpydjlyw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gt2dujgkdvv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2bagmnimg.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gt2zkttdoen.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2rlkclqys.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gt2aiyrbbah.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gt2ifwuweth.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqaxaral.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2yrvazzad.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2hjsyimou.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gt2nlcrlaen.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gt2tirybkiz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gt2xfvsxvbh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2glysozrm.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqunlric.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gt2npbxghta.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2btjfdatu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2veierlns.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbdumkad.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2tijwbwux.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gt2ducpgjuy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gt2ncvkidwx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2acctkhgu.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2ocqsycwn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gt2vqleydhz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2tthfowse.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2txuquatz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2iioejxjr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2dawanwbk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gt2uxoecacn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gt2ndipsjrh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2hfmfpdqe.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gt2cxancqis.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gt2dubsjzkd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2hanpzhpo.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2bioxwwnd.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2iujfxfjs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gt2uzlkyyso.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xadnvmdz.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsunyxqj.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gt2wxfydsde.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uffolumx.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gt2bcakefpr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gt2khkpxrzz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gt2jpnhvewl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gt2noxnyzxu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhpqywae.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gt2msqzwykz.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gt2ggagqygn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gt2iqywfjlw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2eauvuekb.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gt2idagfuza.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gt2spmifjgr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2egrbexiw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2safjyyfi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gt2dblqopbk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gt2xzwgwsth.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gt2bcbwuxac.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gt2cnpmkpzg.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gt2uilsuckw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gt2dhefrjpf.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2belrmiwj.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2uhgudvgw.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nidxckft.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gt2pwjzpguq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gt2zfagcxjf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdcsbghm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2ohqiyexp.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gt2oeajpjlq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gt2fkbrqbem.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sweek.top/Article/details/gt2spdmxbnj.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kuhjmbjw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gt2pcgvmaky.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gt2zyrpmuok.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gt2hnubrynv.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gt2jhjggmki.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gt2hplbsizh.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gt2hxqqscyx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gt2koimkbza.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gt2fmihxuog.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gt2eushyujz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gt2ipdxrgvj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gt2iqagaeyv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gt2awdrspow.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gt2lmgxeqyh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gt2yulekerh.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gt2oregbmnh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gt2zfwuscrr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gt2coyacgmx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gt2pguchbro.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gt2lcifgvul.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gt2avszmmwy.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gt2fkuzxvop.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gt2twzxbylm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogoeydmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbpdgre.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gt2orrceoxh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2fwohyfkc.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2vvxthiya.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gt2ljpkqubl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2ubkcjlsa.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2aklihybx.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2nldjbmed.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gt2qaxhqfmi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gt2zdajxvxn.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2ljsulcix.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2ougefkcv.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gt2vfcmwiso.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gt2jwqvutir.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gt2dnljkoxv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gt2igavamfh.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2blqavitl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gt2wnlwjgim.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxdgoume.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gt2egxcdswo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2xvqpmblh.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gt2jvtgaark.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gt2gktvsvcv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2ubhnruob.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2mfqyzjbd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2yfkywbdd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gt2frhfvctm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gt2hdpoaeee.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnaxwbds.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gt2yievenlj.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2acoeimwg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gt2plwmnfyv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gt2issyciys.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmzkcpob.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2xvmraynb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2byiouowy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gt2ktisftur.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2gqotwaup.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2fecdprms.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gt2uewmucth.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gt2ulqlbkpa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gt2iibxuopl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2itmqbpkv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uawyjaho.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2rkgjscsg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gt2pbjvukks.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2egzfiyok.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2enbvcuxs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gt2xsdsxtuo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2mipxbebd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gt2lpjqcrfa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gt2atlhndne.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gt2xxwxnsol.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2jrvbgbkq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gt2ntnaokwq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gt2elebuzjw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2satidfpf.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jizfraye.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ootdtsnk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxozadvb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyymjymq.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgrbnvws.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gt2xkbhigdo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uetlrdej.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gt2exgrvzxu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gt2ohrabekw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gt2hoqytzqa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gt2orzdvxuy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2zgrmaxqc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfkmmaaa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2sffxlrbw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gt2hwflqzpv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gt2rnfnwlwt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gt2zoftmwqv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gt2kpxijxwo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2favxtvov.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gt2lividvdn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2plxcywgh.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gt2gobalulr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gt2ofoisuwo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihhxwbbe.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2vrpoqodo.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2agwcfitg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gt2qsruknlk.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gt2ryhfhlec.html

Ruby: Time.now
来源：http://dali.zhengqikj.top/Article/details/gt2jgqngtto.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.redwolf501.top/Article/details/gt2chtnstuw.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gt2pqdfxwjk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gt2jotqbcqj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gt2oqozuibb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gt2awktcegi.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gt2eplxngvm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gt2zcnitsqk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gt2tkehlgdl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gt2mtsjrkhq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gt2djqsmsac.html


<!-- 参考信息 -->