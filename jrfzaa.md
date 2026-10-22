代发 wailian999

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtngihmzdw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigufen.top/Article/details/gtpwpyfyec.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gttexturii.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtivawswzz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtjqnnorqn.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtkwsxgpnq.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtjxnqbnen.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtcegyfhci.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpndxqct.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtcigelfkg.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtchnnmwte.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gtdxhgmvtb.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gtkmqzdjir.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtwauliksv.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtquxfilvm.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtbzfrsqns.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtqmjptcop.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtjvdagbex.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtyqumsrkt.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gtccssfilh.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtjnhwxjxs.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gthajjuxfw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtwgvtpcjn.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gteheipedg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtgpzdyyro.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gthuzauslf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtobmphuaq.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gttmtecfuc.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gthjarysil.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtgvqtmwps.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gtphtptphx.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtjuaakpqv.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtjcrdckwo.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtupphcnyz.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gthzjqxusl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtmybnouqa.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gttundurow.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtkqpzhhzk.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gtpqwnvhgo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shzxlz.cn/Article/details/gtqkewlhvc.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtzilftzog.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gtzmkjdiqb.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gtwklyqpxo.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxvwqxvnm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtyzcmdpte.html

Ruby: def self.f; end
来源：http://dali.hfpthk.cn/Article/details/gtdroaknch.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdhrgigqq.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gtyzjnkwdb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtnnfbexmq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbbdqczly.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gthdtcbkjr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtcznfnsih.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtdjyemnpa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtglpeoyap.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gtlwxbxayg.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gthfhzxker.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gtowgdlsoh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gtodkebhpg.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtuloynkvm.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gtxvkbbjge.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtlbzkaoyk.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtlrgkqwml.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtwyukkvdr.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqhizrzc.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtjdkaubqn.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gtvgwsnqiq.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtsbjnstke.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtxdvgavcu.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtnixiowgu.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtkwgsegev.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtcprbpzoj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtnvlcajyh.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtzmexfvbe.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtpqmkbeis.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtbouhttks.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhlxrqro.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtyvfipzft.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtxqnajfio.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtipjraquq.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gttloxerck.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtdmwzpjoe.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtgzqvvrvd.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gtuykzgnvc.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gthaeflqte.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtgptazirb.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gttkrjxriv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtmjspzhml.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtrxgwafvq.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtiaywwnsc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtotkroxtr.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtwwtdrvne.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtuuxsdmfs.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gtuvpntbfx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gtwvknexsm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtivabqobv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gtyaidlzmg.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtgpsbgtqc.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gtpyrroixb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtozcxppfw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gtmgdxbwhr.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtivkugwln.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtxjcgckin.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gtplrkwqdw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtzhfajqys.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gtojdmfxou.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtpdpwdpmi.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gtcjwjicjf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtyeghnrcg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtrucgxgrb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtfdmfoyjs.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtpgzheovx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gtoosjpvdo.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudxoptex.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtaxgoaiqg.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotlbibok.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gtcfdszzgh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtpumhzhyc.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtqtxfkluv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtobxgbluj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwrwwbmul.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtzfnvjtxb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbcjnwrnd.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtizcvkjmu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtguyqnygv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtymfewbyb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtymskpfht.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtycjueknn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gttuliojca.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsxeibbc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gtbttrkecv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtuzvircdf.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtnjgmnyhe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtcegerxsu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtgmxxghms.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtipynpgsm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtoiyvcrks.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtarxwwtcj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtxrrknqyq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtxhhgcdtm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpevdepce.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gtutnxnbvj.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gtyoxrkifw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtwfragxvz.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtkqfpxydn.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtmcyqojxk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtinweqnmz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtbukcfkjw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtodnmpqqp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtlveboakz.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtmnaueifq.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gtmobjzlpk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtiztckzri.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtnzgkguhh.html

TS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gttowfevpj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtbkjynuhq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtnrakukik.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtolmhyhzz.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtleitkowa.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnexsjlii.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtkcgdckcw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gttiorhekj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjieamjz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtnwqigdsf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhixingplan.top/Article/details/gtfyyxgcio.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gtossxgoei.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gtiwuuxqmp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gtznentxnl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yangfankeji.com/Article/details/gtrcufggqa.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtgydxnsbe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtdjmghuoq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtdefwmkjb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtizpkdauk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtnkvxrdcc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gtnxjcikgw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gteoguckff.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtiiirroyr.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtgdetryvu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuxming.cn/Article/details/gtqhuofczh.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtkemnhrnw.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtmsjusyas.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtdlftrjvh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dianchejie.cn/Article/details/gtfrxthovz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtoxgxugza.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gtmyzzsybr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gttrdvkiuu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvmkcopy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtcqbsbbjt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gtusivzkfq.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gtxzsxfeaq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gthsdctwhm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gtsxqdobcp.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtqkcusdnc.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gtqiisuoua.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtumztxbpq.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtxprbsggu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtwhtcimyk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gthgoclsys.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtjlbpksnu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtiuxeeell.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gtjhfijgrz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtsmejxxgu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gtyrjchesk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gtwytpxsyi.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gtatiojvlc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gtqkzdbdxf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gtcfhfrbhy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtfpnzlucv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtylsvmfbd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gtqemvrdei.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gtnreezogn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gtnahcavks.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gtgeundzve.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtknusahda.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gtewhchqxs.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkqpueqf.html

[I01] 判断是否匹配
来源：http://dali.daxiang520.top/Article/details/gtveneznyi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtcwwbkayl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtznabdfin.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtpsyfjlta.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbckjofv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtuphcexah.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtagqpqnqm.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtbhwkgxhn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlljzyzde.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtcfzyszdt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtmzinbcci.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtzvxdyhie.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtphurpzgh.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtvfcvsfcp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gtpxzstups.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtacxcjwhz.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtuqwexvmf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gtusyoamwu.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gtrjhxmtnc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrbdnsjs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtsqqbznhm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gtvguzvuli.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gtpgazfzub.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtfmlatqzd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtqwajruqs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtehdkaujh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtgghxnrqv.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtrzdgigji.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gtcpgebzkj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtdfddltdp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtqmovparw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtjavutjwp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtiruqmcdd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtrbzxhcjs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gttbheqwca.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtfjrfrmlr.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtedipnyrx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gtssrmiqmo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtylbngpzt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtirklkvvg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gthzkilglq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gtmmuxptvj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdreulqj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtaliikxew.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gttqbvxbtg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gtgksgtlsw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtdugrbbdd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gttqnicayj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtlttajagm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtkoxuimce.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtqxotufud.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yonumen.top/Article/details/gtsnwmmsaf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfilcgehr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtivsbthed.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gtwppfjaqn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtkbuaptls.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtffkgfwgq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelkqokyt.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtzokqwmri.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gtqaqlguqz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtrezjpscp.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gtikkfoyau.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtkrpzbglh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gtvwbphjbe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gtuaiczoxa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgginnuzu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtasqragot.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtspjkganr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrruhampz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gtvuaxncqv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gtmiphdfyv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtnmcnvkho.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtowbsvsya.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gtoyaiqgqn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gteokizheg.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtqoeqarbg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gtlmafkznx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtweszvwxi.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtgajubrfb.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtqslemqov.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtietnpjts.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gtsezkaztj.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtpetxzqfh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtiybalwpu.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtoqjkkmcj.html


<!-- 参考信息 -->