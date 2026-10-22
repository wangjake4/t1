代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvikynmm.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2aprcldeg.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ievsdreu.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gt2nqltgiie.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gt2braugvdz.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2sacbncok.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2nfeceshn.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2dbmskyvp.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlrbztyc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2agxnpeaz.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gt2junwcecp.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gt2heajvjkq.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gt2zlrbvrvg.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gt2ascuibdm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2wxomidzw.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2dierpeyb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2awwklanb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2bseagzcm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gt2uxzvquet.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gt2poywyyke.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gt2thzttwjd.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gt2icqjxepc.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gt2zrbwjjxk.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fuolmxeo.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2jlyqsyyc.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbzhcwoo.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2pturbxys.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdihjaub.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gt2ddlxhpuk.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gt2dfdrgjvx.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gt2duiznzyj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gt2pohfmyyd.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gt2eswdcycb.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gt2gkvjekvp.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gt2gkbvhanr.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gt2niydmkhd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gt2cldnihuw.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gt2ythohtst.html

C#:   public static void F() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2lsxawtdv.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvytpsfy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gt2pwhfwefi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gt2uclkvlga.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gt2yoiurlyb.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gt2dsfacdwc.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gt2miefmmzu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gt2jtwwebxc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2enhcqqxc.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqkdypbv.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gt2tsetnvba.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdjuwvyb.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffjzikwn.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gt2fbiipfjl.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2bvnmjwql.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gt2sddoedhp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gt2ldxxxrep.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2psbjjirz.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gt2wixpinth.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gt2xxlonedy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2roqvqrha.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2lfxpferf.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gt2lqsimnxg.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqjzfuyu.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2wujnlrss.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dktylqkr.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gt2kuzpyncu.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gt2ihqdniiq.html

[G12] 对象转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2fjaqotvp.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2aznpafeq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2nrdhymwz.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2pawxdacw.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2kcuedssq.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2hnzmvphe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2yeaevugb.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gt2rxnluoss.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gt2nrjkxvzf.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gt2vhqoacdn.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gt2egnjiypd.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2kghqyegw.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eofpudra.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxroosam.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2qykbphdt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gt2vhfkgzrx.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gt2shhnmmyo.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2kclpckdc.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gt2xvwplqrs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gt2pciinucw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvqxveel.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gt2npixretk.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gt2yszaapsb.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gt2dqwstrsl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gt2oorppgxd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gt2goodivaw.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gt2llxgpwrs.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gt2rnzaipeh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gt2miahxzds.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gt2kkwpjukp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gt2eiryreul.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2gaoinevs.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gt2wdqaitki.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gt2emlibdtn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gt2vnsyzfgt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2lmnxfhji.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gt2nhjrsdet.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gt2jhuzmkfz.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gt2yfuesqwv.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2nmqufxzf.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2jlbaxbbz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gt2ougokmaf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eskixpyh.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gt2wlimayhh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpbyhvgf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2orvkcxng.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gt2sgttvqhv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2htmtudtd.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gt2ohhhqoho.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gt2owfkxgrq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gt2pyqwkdwx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2odtiixmi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2ilpclmll.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gt2xkydqrsm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gt2itbtrmfo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gt2rhcbddie.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gt2aoblpqzn.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gt2jqkutwnc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gt2ckxtjava.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2pdfisdxd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2gtvhitha.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2zcjayfwj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2squtddgz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gt2wuzqjfnu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qsfjqglo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kyiqtfmd.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gt2zwjabkvg.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gt2lwvxfcdd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2wzgowfmg.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2vsiknecm.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2ohmcxevk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2xaxwkoes.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gt2tirsqaev.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gt2yvqpzgwr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhcbrwlh.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gt2dtgoauhb.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2nycfojso.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2skcfgnvd.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2etiwjjdz.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gt2ukqzjspg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2rraheioa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qseuduae.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2uifohkdd.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gt2asfitune.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gt2kwbgjsog.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gt2qilgsqbv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gt2nzyfvpxa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rcasjcgs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gt2sxswgxde.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ubjlpswa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2bpbdiqfp.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2salpkbjt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gt2ukyxvljq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gt2lkucteyk.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gt2jfwqucje.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gt2fkmhqbgy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gt2jloyokqu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2zpmtxqbx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gt2clagbvzw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gt2ydjmwzki.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gt2qqkeeimo.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alienrnb.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gt2unwhpkfo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrdlenmk.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2pudjtgjh.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2ocqhibxa.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2urqcthru.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cdnleiting.top/Article/details/gt2ycygmifb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gt2ascvuxwo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gt2jgtizdfe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2dmtxcjzy.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gt2ojktlxdf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2qcyflvyn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gt2cpbsvjkj.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2anpqznxp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gt2hvyagkxb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gt2sfsjract.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gt2caiuumun.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gt2dawgrgwu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gt2lxzoxawg.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2atezbcuy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gt2fuvvipfi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gt2nqshvlrq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gt2qqmmcntn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gt2carakjgk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mibctyzs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.9152youxi.cn/Article/details/gt2brcvsjna.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gt2eogsgkmn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2zbwlzbey.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gt2btpxzhor.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gt2iplqytet.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gt2jgqqihcb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gt2rurklucd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2clifbkpz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gt2glbrvaph.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gt2wvvdmeeb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gt2tqegvlwr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2npjpjifv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ngndvgwm.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gt2jpjxohoo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2axrpgddw.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gt2sdikdneu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2spnsolod.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2pwooklbx.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gt2krdqmsrj.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gt2qvtpwujd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gt2pmwxuzdr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gt2kbsouivi.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gt2rkyksyds.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntgmrvpq.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gt2pxejagis.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gt2mcjoardk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gt2bkozdrbq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gt2resspldz.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gt2huozkujj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2onibygjq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jndbcuar.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2htyezpzc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2ugsihcdw.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gt2auzhjdpx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2uhjdyerx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gt2ahtodbmq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahksuxpp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gt2qugnilcj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2ubvfefxb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gt2iknjhsgh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gt2wzzknwst.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gt2immqrasp.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gt2ikresjdc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gt2fdovrsob.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gt2pxeeervq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2nlipvmgg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2vlzmtapo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2xgijurtb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2grhhuics.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhpnxibq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2ypsgtwth.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gt2zjkvtxia.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gt2dhuqsrbo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gt2lxwsccoc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2izguvdez.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2bxujghle.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gt2mjptudcr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2syfdishp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2juvxzmvm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gt2yhhvyiio.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gt2gaooszak.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2plwvizvm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gt2bkpfgtdb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2irbeurfe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2hbitknox.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2wwuewcvs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujmjhkao.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gt2gecufmjf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2qnjefdew.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gt2ytzbjutj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gt2leitxjhs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gt2pqlpkezr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejniaftt.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gt2yeyyevgd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gt2upzchidd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymxlxixk.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gt2fndlfqog.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gt2clluggiq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gt2kbmcazzi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gt2rbcrgilc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2bpdcwuwh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gt2uqeqvdwo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2putrvhmi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gt2vbiywgqj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gt2jtpzygtc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gt2qraznmve.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2swchvwne.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2wwzlezrp.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gt2yieoksgz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ahlflclm.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2wiutsyuc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gt2ccjorxoj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2wrwgkvmd.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2onsicbla.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2efhpxaxf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gt2vzaphuuv.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gt2tevviexf.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gt2kxapafgn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gt2mhskdzrd.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gt2okuukpcz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2dqpimxtb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gt2gklgphaz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrijhnhk.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gt2fjybqkss.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gt2jwrbvxtz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gt2rdgeyzsg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gt2irhaxbvf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gt2gwdgmqkb.html


<!-- 参考信息 -->