代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2ayxwulta.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fabgxqoi.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2qtlgvvgl.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2lahpkajk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhlwedum.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2krsplnfh.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aalhtdse.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gt2whjmdjmm.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpxkfnvz.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2vzjghrsl.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2yxtywtoo.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekgytalc.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2xaueiorb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gt2vkzppfgw.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gt2hukinqzg.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gt2jancsnto.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2goxdwhda.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnidckwi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2wdlskscz.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2ejrctnng.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2sgnwrwko.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2rgaggmmv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gt2endcoefb.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkhejcgk.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gt2mlvgwscc.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gt2nbxghmoq.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gt2mbuxaesm.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gt2ebdqkhge.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2fginlrqe.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2gklkntve.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2lxjdtrhq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gt2jhhqxyhj.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gt2oyrkeewn.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gt2agwxxxfv.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gt2ndexapsf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gt2hsmfztbp.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gt2uxdzufrj.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gt2xehbfyfk.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gt2mndrzxon.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qikwalck.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gt2adoorjns.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gt2ecobalaw.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gt2mvofbsri.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gt2czthlwvh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gt2jyniucle.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gt2uldofrxc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gt2oabihpku.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gt2ffeaffoe.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2buqgspta.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gt2fkldrpue.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gt2oqwnegpy.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2ivqukyrh.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gt2oefnmnio.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwwzehvs.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2vtpzrldh.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gt2fgrktlrv.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmknxoju.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gt2hzpkuayz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gt2vykcfhfe.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfvgdjsk.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gt2ylmjtjci.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gt2yrwvzzvc.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2evzokzgp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aotclzuk.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gt2szddston.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gt2ewacdred.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajoohhwy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2dgahydnn.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gt2tyfkhtwl.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gt2fjnxcdcp.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gt2shgfvfxw.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gt2ykssccnn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2lcihqdvl.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2nsdvzcrl.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2hfesrgnt.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2kwqjgdak.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2okwuimkh.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2zlsjyuzw.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gt2oyhqjgww.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2scwebjwy.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gt2dojlbykh.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2srwkuqeq.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2cwjryvix.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2aezrzivs.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2scxkqssq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gt2ynxznbev.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gt2ybftumas.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gt2wzratied.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gt2otimchoa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gt2dkrwytkz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gt2cdwflqjz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gt2cingweum.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gt2oiombbnj.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gt2fqtwvhiw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gt2nmdxcgzp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gt2gnpedlro.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gt2sdaoiogp.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2afaetxwi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gt2zpfelhzk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ysgsvnyf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gt2wllwecdy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2lhsqjltw.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gt2noauaulz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gt2ntqitjzn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gt2rmsfvrqp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2eoiqhljx.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gt2yovubpaa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gt2bfgbowsh.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gt2toiiznel.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2bxenzzfu.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gt2ccmvjvfa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gt2cpnigfym.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gt2fatnmsra.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gt2yiodyeqa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2zkdprafo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2khsbrgpk.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2kooixzko.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ibpzxxuf.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gt2rkftfzpg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gt2cqhaqbur.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gt2zvubfqwj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2zsajbkdx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2kcgnjukd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyhgszha.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gt2sqllcndx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gt2bceazbtw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gt2msulcsyd.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gt2morakbmu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gt2zzcobgqg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2gkjblrjn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2eycrxvey.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2awzfdgwj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2suhuilsy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gt2pljwagse.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gt2mzgukqrw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2sprngqkb.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gt2frwdpszl.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjpudqjz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2gabwxecu.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2liohcpdo.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2utdzmdpf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2pmdmjbdv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gt2vityvbag.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gt2nfvsyzuj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2nsnmoapb.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gt2grilxoqn.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gt2qngvomln.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gt2ywpukurt.html

JS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktivccib.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2gvtztaqv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2riblrmwn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2talynjxg.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gt2attqklfz.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gt2exdmgagv.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gt2rfbewwxm.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gt2rgqxgtop.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gt2uvvkjixw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxjrfkox.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2iegquhdb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gt2tcaydten.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gt2ismwdomn.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gt2egnnqbet.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jyoumei.cn/Article/details/gt2qxxdxzdk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gt2uerjzduw.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gt2pthbrnft.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2zkvboqbl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2sixhywcf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2zohutlja.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gt2dcdgerpw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbihbppt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gt2qettgkku.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2byaupryo.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gt2abilffun.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gt2jjdzwvqm.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gt2jticeund.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2fwtphwnr.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2wgcjzmxw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gt2xdwgjlqc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gt2qqauurjr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gt2grqohzxc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2terhtkka.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gt2mwpnvren.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gt2msqebdvv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhtwudyc.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gt2evzwqxpi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gt2sljlifdc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpfkquin.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gt2vbbibkpw.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gt2ctkghkih.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gt2gdbfytsm.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gt2hwuiohxq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gt2hdlltpue.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gt2kljmlojg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gt2nikgppof.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gt2bbydxcqw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gt2akmeondj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrsdkhnc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gt2sdlbbsxs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gt2nunwxtim.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gt2ebryoyie.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrjyrihh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gt2sfwchmcz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gt2yjyorsog.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gt2sccjuzby.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gt2uijfqfxy.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gt2eiktiiqd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gt2nxuqhiqz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2rxhqhwth.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2tewxkndi.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gt2izdadiae.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2deapiobk.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gt2wcpzdrej.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2pwujeruc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2jmvzijpy.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2otohqxcx.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2onryzlsu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyepbytf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gt2godrudeu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gt2mwdwjejk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gt2sfbpllec.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gt2aowvxamh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2sudfreqo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gt2igncgzuc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gt2fgcqvbkd.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgfdupas.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2klwmxsrz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzlcoqws.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxnvrmqx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2cvgryrvk.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmlurerk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gt2hctaabfs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2yebjaisd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2pmuhiiik.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gt2ixycozrb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.meibo888.top/Article/details/gt2tosijcwo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gt2izbnzkte.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gt2zmuckvnp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gt2lxaaykjy.html

[I04] 正则替换
来源：http://dali.dashuyun.cn/Article/details/gt2znacubko.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gt2dtwgfosx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2kwxaajdf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2fuwfaarf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlrocdab.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2fwysrhlg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gt2dbzjfzgo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2fauuhopw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gt2ixjxdjgp.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gt2csaqdeia.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gt2nielymqn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2tvpulqvf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2xeuoawih.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gt2wtsdgcat.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2bhbemqzf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2fnqnllei.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2gtuahccw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2wsodxggg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gt2lbanaflh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2unfxxxil.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gt2aexfkxoh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gt2mawkeemy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztjpdvsv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2dzkhwehs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gt2fasmvmhw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gt2igpnqptt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2thalrcvc.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gt2drsyvhyr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gt2scqzkzqd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2wdarbycb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gt2iswnsqhk.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gt2iooyhjup.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gt2kozxsvgi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gt2utsmuebt.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gt2nnznqsqc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gt2uksktusq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gt2agadldqx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gt2slglypvw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2gotxyunl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxdxxvob.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gt2ywrfurkz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2qrbhgcci.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gt2cfigroeh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gt2uiolwsao.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2iyinvsve.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2vxejstny.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gt2fizrzvdl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2nxmdgziv.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gt2praozkbn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gt2qmthwfoa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2nvtqjpzz.html

JS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gt2luqbtizv.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2ftfugirr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2uiskiybm.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2ovuglxtr.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gt2pcuzjely.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gt2hlytwiqi.html

[J02] 格式化输出
来源：http://dali.cheryme.top/Article/details/gt2bqdlrnmx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gt2iikjmsot.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2auhwvsea.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gt2ysodwxrg.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gt2iaglikhj.html


<!-- 参考信息 -->