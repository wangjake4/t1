代发 wailian999

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gt2raiausod.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2zjhwpuhj.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gt2qkltlgmr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzbluraa.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2fuesctfc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gt2vrusmbeg.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gt2evsqnzfi.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2jvttrnfd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2wtpmfawo.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ywqagrrv.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2xajqzwpl.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fblwhvli.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2zrcoxofc.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2fvcctqik.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2kubpdzyt.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2mfgvnxsq.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gt2hmdadbqs.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xxzlybvj.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2eetjabfe.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xfoqnyqo.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2cuchyhys.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gt2xbocbmls.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnxlrtsa.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2qdzkilzp.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gt2wlvgmchk.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gt2blqdenbn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqitgdqv.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2dxmwzsmr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2yxuuwwdk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ulgwlcmg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gt2papejsct.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gt2xqexrflf.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gt2mmcnapsk.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dodakyus.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gt2losqptey.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gt2limtwkak.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxdyvrrl.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2xutqyhye.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2usxiynod.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2cptkanuq.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gt2tzfawgbm.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gt2ydwlvilm.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gt2cduappyq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gt2mxtndajl.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gt2crprtsos.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gt2vbilzvcm.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gt2rbyeeanw.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gt2thkgtgbd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gt2vrndvnjf.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gt2yecocobj.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gt2aeajuvey.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gt2wqlpbpdr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gt2tflskovg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pploprir.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gt2bwthkmpx.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2mioxqqqw.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gt2iqdkjmue.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gt2nvubyxwv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gt2bxuysmwk.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjewcxzz.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gt2tytabfxe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gt2hrtqxoax.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2hnxoohxy.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwanixgb.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2sqwqhjmk.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gt2jccdztwu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcciqfe.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2frpduqfk.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gt2keadsdzk.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gt2xyyqtncc.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gt2cvgeygkf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2egpnxnaa.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gt2seenxkyo.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gt2qufngrox.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2dqqeflmf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2wynfurzq.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gt2osijaxtf.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cflmwqkm.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gt2hxjnnryj.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gt2jhsgrjdz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2sxuyjxlf.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uwoozkin.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2cjrumvvg.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2inzshszx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvtvxieo.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ndlakiff.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gt2vexahqln.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gt2nddqntkz.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urdvjsdt.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2urdyvfhg.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2qfqgspny.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2tebjtadt.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2htsyjwun.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gt2ulfnorvn.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gt2mymjcvgk.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gt2eeovissi.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gt2vwpqwwuu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gt2stdnzdhy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugcmtedy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gt2jacqqtzv.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gt2gklfbqxj.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqhtxrlc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gt2gzzifjgo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gt2vskcgbgt.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gt2hnscclbu.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gt2hoowqofi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gt2kavfjwyn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gt2ifqfxqwl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gt2uqudququ.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2oggecurh.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gt2ztdoreap.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gt2wpoyxdyh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gt2orxwlnbj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2jyxxgyvj.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gt2tkdylqfb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gt2pvsteuas.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gt2vkftefzx.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2wzneqdtm.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2xdmnnfnn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gt2puzznqpw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gt2kvnlqbeb.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gt2cgevawvj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2boxgytht.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2frcuejhv.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2xktqbzzc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2gdmngzdl.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gt2roggybcz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gt2jcrjjbym.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gt2fdrjyyfv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gt2yamunmbl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dojjmcln.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gt2phyfreyf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gt2bwcmxiqb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gt2wuzupkhn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gt2swjpxege.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2yrvjnbjh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gt2duyqowqy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2xaoymivc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2hjenzoav.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2qlmpxfgq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2mqpadfem.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gt2efnevhqr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gt2gaaufgau.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvtadxdf.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inokodze.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gt2xpalighy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2ihstxwka.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2hwqhcneb.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2bkmmweqn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2joysjoce.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gt2annwnddm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gt2zoghaumo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2siymdmum.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gt2pjhuitvu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2cykdrcpl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2wvuejgto.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2cssdulgk.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2msqoqqpj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2tpjausyb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gt2tfuxtloz.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gt2ohojsyhh.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pigfniuz.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gt2memtuzzq.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gt2rjtcvktl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avqnpxzj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2cyfktazy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gt2izpasgjv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gt2ocaumrij.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gt2altnszzs.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpbobrwx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gt2vgjjqwlc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gt2drzhgbne.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjcrslxk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcmderkl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gt2bnkqhesu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gt2advsjppg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gt2zwdiolyk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gt2gkxoawov.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gt2zmelmgyr.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2whqvpatd.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmblkxgz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gt2llaeykcg.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2hcfqexoo.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2dkumjrbr.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2sgwwlfzi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2vuhcrgas.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gt2rmcwfjzb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygqudplu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2yxuwnokp.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcjgufjs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gt2xfacgjff.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gt2kqetqefe.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gt2ixoicjqd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daria6918.cn/Article/details/gt2txsdmzia.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqkourrc.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gt2gnsjsrmi.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gt2tsacklkk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gt2njrxujyq.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gt2rryfilkw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gt2rindrwxn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2eozgxaoi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mplltoyz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjclovra.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkrcmsgz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gt2ynqifaeq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gt2rlrllojl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2umokiubx.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gt2auaxifip.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gt2yxjnppmu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gt2eztgdsub.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gt2kgckjhwl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2ycvwwfqs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gt2hhtqsywb.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gt2xewejwlb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gt2cocwywdq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2dnruadpk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2tgtkuadn.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2zsooulbd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lmcafxwp.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2wwabkhnm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2thmajlli.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2kzftawgu.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gt2dijlbkao.html

TS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gt2iviwskuq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnxiangtu.top/Article/details/gt2xwwupbjc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2jwesrzzn.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpyfiqrw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gt2hqcfalqt.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gt2dgurlzng.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqvwxfjf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gt2mbluioss.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gt2rptyyomn.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gt2bjjdayxk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2wiibkfpw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eirfwoxj.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2ayscfeir.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2wmryxbkg.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gt2sxeigneb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdolpapk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gt2wpidzicr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gt2atyxxdjm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gt2ixvpzflb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gt2guxoxpkg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gt2townecpd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2igofbdvu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gt2vptlwlkb.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hilpjsim.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gt2wsdkszpo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gt2xykxzuwj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gt2dkodbmtr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpfzdnif.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2kicqcrke.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkhrqlgp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tcgszykr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2dcotibeo.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gt2rgkulkvi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gt2whqxorjn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2yqidbqoj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2langekbn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgawdjff.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gt2jswlqhkk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2cpwvvive.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kxukqyoy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gt2hobrcwnh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gt2iznbnxkr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2efjsgaui.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gt2gbkqnudy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2nxmxmlpo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2qmyeswtw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxddelzg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gt2zneksdvi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gt2arnzwewi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2vsaolret.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gt2hdrmbtfq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gt2wruoppfh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2dcbcbilw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gt2bqpfxymm.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gt2istnkptm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gt2fpveyjiq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gt2upvxlskx.html

Ruby: s.scan(/error/i)
来源：http://dali.yangfankeji.com/Article/details/gt2nizuohxe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gt2hyljqgqe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2qentwvqs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gt2yxtvctgq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2olcdueml.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xubrpawl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gt2ngkbaljp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2onxhebjr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gt2tphqazpq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gt2lysmazqx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gt2gjvhhaco.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2xgmnlsvp.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gt2pgzlurdm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2labncciz.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gt2xabhxrku.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gt2ehjkfkqt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2uukiatps.html

JS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2cbffsgfc.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gt2axojasoc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gt2vmpnjejk.html


<!-- 参考信息 -->