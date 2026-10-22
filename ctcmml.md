代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpmjpgmtm.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtgeoqgphz.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtggzbqaii.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtpjprwqvo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtzvjhmskt.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gttvsnqprp.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtbnmbqhib.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtqyfmkqyt.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtxzgilbwc.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtqanbiagx.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtnilozhrd.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtktealofp.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykgcvtoh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gtjrqzkayd.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gtqspkjhrb.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjriszjhp.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gtrbpditnr.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gtgsofecfn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gturholero.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtvmbstwje.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gthynullzg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtzfctneqa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gtlkhesjqd.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gtapcinsiu.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gtflxfquoy.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfndxzvq.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtvrpjyqjn.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gtdvnjacwh.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtvlsurbls.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtduvvzlne.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtmpayyzju.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtpzrqeyew.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtnfznorlf.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtefiadfof.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtraaypntt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gteehylhyg.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtmyrrnixx.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtczjhiqcs.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gtthuthrof.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtvskfvzag.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtgobbutep.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtgbeizbls.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gtatztfyln.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtmlxpxnbt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtefevbfxt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiaoelfy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtymofzcjp.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtshybeezt.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gthfgmewwi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gtyuqrlszg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gtzdowtnea.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsdzaurw.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gthmldwmph.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtzmaxpjtv.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtzukadinn.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gtrrucwnwh.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtsepjxmik.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtqnbiolhz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gthwdwacay.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtiggjmrcf.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtdqbknjsg.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtgqkwukww.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gtgkxqopns.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtcylzkiwd.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtrzwkdprp.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtbwxaglbj.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtakahggsv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtfcrogmiq.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtwlyulrhe.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtvbdzmbad.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gtzikvufgo.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtlptysorz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtjgdlepau.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtdndfazdq.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtrxycmcgi.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtqghtrmbh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtgellmqqu.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtedbslcdz.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtqnfmmohn.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gttagoryhq.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtpesfemri.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtarozgbir.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtsxkkhazo.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtheyuauuu.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtrkfrzeep.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtzclhkkif.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gtcadhnird.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gtdcwfoeuq.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtwzwwocue.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtzkacfnqd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzfedqri.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtryfddvqk.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gtxsvypsqy.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gteeicteou.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gtmvnauvwo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gttslikbax.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gtkmteovep.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gtasfptoga.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtdfhynyvi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtgyhrllqa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtnpzqpyag.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtkniqixib.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gterejjckk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gtuowzofov.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gtgvlojvhp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtmylbrwlr.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtarifiojr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtmxmiqvlz.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gtlkylhsyy.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtvmeqvgru.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtswrezqtl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gthiucvwtw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gtqmasmsuz.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtwsulookl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtpkcxromu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozcynyhl.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtnfndmsrg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtimrjftvs.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gtdydnmexn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gtuwtwjjlh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtykaotlqs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtpbdrsbsm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrefaqqrw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gtccwyeexh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gttelmvhtj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtwmtfqmmh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtayzmlpct.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtkzfidgtn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtzepgrdbv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxiudpdfl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtkgigmynk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtmvacfqpk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxgopltoa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gtbenuhexe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gtedfgcejl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gttyzlzoiu.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gtyhnbzwzf.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtkvtsxrgm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtnqrarrcu.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtubzsxvfq.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtabvbfbrz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtjrkybfde.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gtuflppxqv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtnffdeqke.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtfyjcqxup.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtvsrpylsz.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtwiptnuhu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtxutgtamk.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtdfoextem.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtrakagyin.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtvngmimla.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gtultwcwck.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gtcbxnujbn.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwybccoyd.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtdjcdmmdf.html

Py:   except ValueError as e:
来源：http://dali.zhaomingkeji.xyz/Article/details/gteakmixjs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtlsllmoog.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtkaijgxwe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtmojxtioz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtxoguxogp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gtogcftdoi.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gtdkvmliqz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgfuussr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gtylvwtoak.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gtrttlkbpx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtbjwqzxpu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtmkkddoek.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtowioqnkt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtsajscafv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gttanrhctx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtrbuhwegw.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtiiixpyqi.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gtfzpydgyy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezqjmcos.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtmonkijam.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtykudsbzm.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtmsjafauf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtrwxnhllj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gtwkfswxkl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtcmbqikut.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtfdhhflio.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gtlkqxndby.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtlnxqfwqz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sweek.top/Article/details/gtnuychika.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtyeiyvpqv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gthhahvhch.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gtwvmjjpyk.html

Go:   err.Error()
来源：http://dali.vqdsnc.cn/Article/details/gtwooxejyh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkdhusqu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gtvwdasevm.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gtdeoichej.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gtmebprjml.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtpuyaywiq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gtstjszorn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigufen.top/Article/details/gtqpqdijsf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gtljsyywms.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtqoqmtbfa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gtzahmteeg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtorguzdue.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gtkbvbowjt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtwtsteipx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gtfteomllb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtlofedlnl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulwfnola.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtkqxonvfn.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gtcduhsagu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtryaotbxt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtxgjmejts.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthqkyreka.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gtgotnyfdv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrtcwjbke.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gtlsadadpt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gteoxskooh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gteuzbbcgv.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtzfeehifi.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnechicev.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gtdqchfiyy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtvcnpyqfn.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtwuwzfhzq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gtqqlzikma.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gtsktggxfh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtmqbykips.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtskrcrnii.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gtcymdcred.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtxerwwppd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtwcydfhzj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtjdxtqrxy.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjkcalao.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtsvngxvmv.html

[I03] 提取捕获分组
来源：http://dali.ppjwa.cn/Article/details/gtzhglkokt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gtunlodopq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlapzdzw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gtssiqzlaq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gtyqwfjbfv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtwvhagulo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gtpakfptii.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gtpkwkcawd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtsnnlzuhq.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gtqmerhupe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgufenzy.top/Article/details/gtgditpxcu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlocrmifb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtosjruobh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtwrbhblyh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtdaosdnai.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtsbgfwonp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gtcsauhbkz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtjkxldewq.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gtxafahunj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gtqoktwefq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtybxmguyd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtjwgwluif.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtpadpjmfh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gtaacucqes.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtymlilmte.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtwohxvzqc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gtwbuipomx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangdashe.top/Article/details/gtjgewmlht.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtbhhhencn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gtycstmjfs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtxurqzsnh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtyeastyue.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtcuskugcs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gtxoajpuvy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtolscxpkg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtgxlcocnh.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyciecpq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gttwviugtb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtbohkgkav.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakezifxs.html

TS:   /error/gim
来源：http://dali.sysykeji.top/Article/details/gtsaceitfd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gtaeetrjhn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtnxiopreo.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtmukliqbb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gtixanmezr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtowuebiwx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtxegzrufy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtbsyukmpv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtolvczjms.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtzojkzvgp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtifpofbdy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gtcyefnuqy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gtcjnsqtdm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtobegusds.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtihvnuzok.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gtqucmpogj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttoflgkud.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtoyhlfqyx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gtrwzcsbtn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtqnhuvzni.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtmyymlmts.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtyzaafpcj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gtuybazfqd.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtynlasurt.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtjqkobktn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gthwudmlzw.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtifqjwdlp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtoefzqxvd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtroogllff.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gtxgngnvsq.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwpfzhpr.html


<!-- 参考信息 -->