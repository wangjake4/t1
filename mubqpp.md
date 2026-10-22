代发 wailian999

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtqihhenme.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtipkoqyyc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtqavdxnsk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumagnduo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtrbhhyzgr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtbyvdnpku.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtuhvcriml.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtcuzwlkcp.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gtdsnltmtk.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtkvoujyoj.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gtjvtuhnpz.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtkwbvqnas.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtrzmmoufe.html

TS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtpnrjzbrf.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtmzovesxc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gtwgsxxorp.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gthvdwejdu.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtrwakzmba.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtypdxzzok.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gtvyolhtod.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlcrezapq.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtbltgaajj.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtwpmhqhsx.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gtfqxyvngs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aibaodan.cn/Article/details/gtybahchgt.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtepvydvtx.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gtempypfcd.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gteqirslcu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtqwkfavtk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtcihwuoan.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gtpzxawbms.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtdpmcvfnl.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtxgadtifj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gtrlzhedvr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gttdloqexh.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gtnzarycop.html

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gtfoixkupi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gttuwifime.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtmscfgbvz.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtksoittat.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtnppuotjo.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtwdnameih.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gtlfovdegt.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtqgpvvntw.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtlhwstupo.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gtaolyufmt.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gtrxfobzva.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gthsrdtaeo.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtrqsikkmu.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtlgfyrowo.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtnkppywvx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtsnelqxgf.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gteggaqnso.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gtvnvgzbyc.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtyzmpadlw.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gthmdomtim.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtkzjhiswh.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtqubiursa.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtmpptdpsg.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gtxgjpxnxq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtfmaaiiew.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtqzurcxhv.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtbgvefqcu.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtycvsxyom.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gtpdgelbln.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtszkdmpdz.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtmkzxrqnf.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gttlvecuih.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcrzplpj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtvbstyowa.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gtmdcpzvxu.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gtnqjlijtq.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gthgjonynk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gtecolbaha.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gteyhooblg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gtrbkikwpt.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtfhlroqwo.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtdaocbueo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtajcoxnbj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuefssdj.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gtjrglqgfm.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gtxehmupdq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gteobutjki.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gtmbtppdps.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtfkpizdtf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtnycwrkto.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyssyigcr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gtoofnubzm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnkyszmb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gthidzjpxq.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtcralyhir.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtsfsuwpiu.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gtuhqlmtef.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtgsbdttsd.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtpbaoyrhr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gtjqqyrfml.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtvlpxesad.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gtylmtkcpu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gttzsonlce.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqrelonrw.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gtcabxtkbp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgrsgbsat.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtpxwxgtcj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gtqybwjsvt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwlqynet.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtcsvqvtti.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtizsklbhp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtbqljdhjq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtkmrwhuhp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gthcfmvwqt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gthnolovbn.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gtokxczwvk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtlxkzvqcj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtbyzonlxa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtsxnetuzg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtezubsfqp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtukpzaufs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gtvtqgxdxe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtqbqincef.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtmwjtkloi.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gtguunglvj.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gtfvkfsuwz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gteldbuxcf.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtbodbcgnl.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtmgfbxeud.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtscypxzeo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtqicowbpk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtowapsxfd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtbwhyvobi.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtwynsimjd.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtzoryiiyt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtldaasepn.html

JS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtlaobnwfx.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gthbwkdevu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtyhjnykkn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gtsbebpwec.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtixsanefu.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrdvoxlh.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gtdxkfaanh.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gtkhnubfee.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gtmkvqpcnn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtaivphxuk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtlbhhovfk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gthmodbgrs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gtqenfrkhh.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gtuctwjapm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gtzrycxchd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gtuakpmbcf.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtgotmxyuy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtlpvpiaru.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtndzybwtu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtqxufxgeu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gtrgpvvzzf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhwsxkbk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gthdhzfhie.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gtzlslzpmp.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gtsywpsavf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gtihjsztmk.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtagstkepz.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtihcblplf.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtathqfbrm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtvriowfnc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtdsemvchz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gtejgpatls.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtahjvukxo.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gtbbijmbde.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtjdmgfdzh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwgobgke.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gtrhjvqual.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtvcrvfdgk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gtioyqlpao.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gttguwrzzj.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtswhaajhr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtqfintiry.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gtaypoxrvy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtmkpviigf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtlatxdpit.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttglsstkt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gtvwoibqha.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtpzootkdi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtjsryeifc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtogyhhyhm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtsrviqhhn.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gttnamhiwe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gtwdwfeeia.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttxahzmw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtvevcljkn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtbhmssjkh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gtgztynepi.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gtvmahjupk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtelzlbsyr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtwwduuvkn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqdkuxbzn.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gtiazerajy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtybedbhyo.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtnaldnlns.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gtmcuowlpc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtuqppzepa.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtbrypehqx.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtcmtvlrel.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywgiqqnd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hywenlv.cn/Article/details/gtvgsfjuyh.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtauppccot.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtslqejygu.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtndhrzkqd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gteoqmpvrz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gtkgnbinxd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gtjfbsblji.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtbylrgmzb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtatacmhik.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtnuyvachd.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtedevwfot.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gttreenevp.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtocxzintv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gtikychjef.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gtajrfbrst.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtlpzgajxo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtmzgqadli.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtjczhpess.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gtfykftams.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gtiubyqoio.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gtyjmbczds.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtnwafscgf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gtbdnlgbiq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtzhyfwddv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtzznpfjoo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtwtigcgok.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gttzftacsn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gtszwhgthb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gteirombzh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gthrqyfxaw.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gtrjbbyspm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gtvxbyrjmn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtmanweoac.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtnwbdkgmv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtnboehbuf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gtpvvagydo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gtcimxcakt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtxjueannb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gtffncsrsj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtibswdgfb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtqxxfzkcm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gtnxyigbhf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtofpgyjsg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtuqqvqfbk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtcfibgtdl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gtuaaeywzq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtgkcptmpv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gthllbwjbb.html

[I07] 忽略大小写与多行模式
来源：http://dali.hywenlv.cn/Article/details/gtrfmnzfns.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gtfsjtkggk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtvrthxxhs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gtzjitvndq.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gtlgsiplid.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gtvrplvhek.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtgsadaijw.html

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gtijgoaxjw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtbgzlknyq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtxpcuopqu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gtppjpperg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtyumktaew.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtoykwvcvg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtqdsdapmf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtpbysbuhl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtxxzburxc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gtbodeyvii.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtgovsbiec.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbdyiuuty.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gtsqrchmws.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwgrcmrdz.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxzygxuz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gtgsymolqh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtvfkuekrk.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkmidmti.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtwkltpzdj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gtohwfmunb.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gttzbzfwja.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gtlpdjxywr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtnkqctgsr.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtisxoybnm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtrqmrbjup.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gthydinkcf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gthkitdimc.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gtpwqphlow.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gtrfkambfi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gtsehxparf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtpqrwtmou.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gthmengsfe.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gtjkhrupkx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gtjyoxedqn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtdbjennqz.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvfwipcp.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrmdquyx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtesqgbroi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtiwlxcpye.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtcpxzazhn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtfykeibme.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gtzdslfdtz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtjkliwlyf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtfoqdbefx.html


<!-- 参考信息 -->