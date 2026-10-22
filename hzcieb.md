代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2gunjfdib.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2wlzkhkcl.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uaapivdm.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gt2hdxvmira.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gt2lrwmzjox.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2zzcvmopb.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2qkedjbfp.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pksvvres.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ccyzwwlz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxkslito.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gt2jvhnkouy.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2elsucmhr.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gt2gptfraft.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gt2frdfuydi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2ytchajlt.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2ocdqjmri.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2suzsfatr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2pkswybmw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gt2jzbbsivy.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gt2bvmfiezj.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gt2dpdttzhm.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gt2nenoqbnr.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xamvxaqz.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gt2tmjcohup.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpjqyuxz.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2dywakifg.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2eelmvehi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gt2fvbgcrgl.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gt2caqcfvug.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gt2rjywinan.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pchclyzf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gt2xofanroz.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gt2ucenrfxp.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2nnfupwjq.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gt2oofsrops.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gt2kurtquru.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gt2lfnkvdpn.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gt2mcfpqgpz.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gt2lbedppac.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gt2vfehqlph.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gt2vaailpar.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gt2fbpcqqyg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gt2uswivqee.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gt2pndhodck.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gt2rzvyeiuk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2adtgcppw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gt2qseuhixp.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2ycerdrdx.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gt2mmjhtrqh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gt2dqtbkymh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aywmtzah.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agcfgpru.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2wlncppyt.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gt2ngpztumu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gt2woyhojpu.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gt2bmbmbxuf.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gt2jsjpndzr.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gt2yvouwhwy.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2asywmgzm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2klrtnuop.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2nwbahakx.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2evwyhzlc.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vurundyo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2qbkfwxau.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gt2tjnaejbp.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pimcfniz.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gt2ofqzjpbj.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2nqbykwxx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2hsubkyrf.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwcakltt.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2azulmxss.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2gknlfigx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2zzavacpo.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2yuqptdkc.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2xpueaqri.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gt2sxupnrff.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gt2cbjwlsso.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2zzbdbvln.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gt2xumiipab.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2fkvbeikx.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2qjbunncd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gt2rhyvklym.html

Ruby: u.is_a?(User)
来源：http://dali.hfpthk.cn/Article/details/gt2wylytzvd.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gt2rpctaezz.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gt2fghidrvm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gt2wpxekgfi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gt2hdcuvefg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gt2vjgcoiwz.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gt2wrwybqru.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gt2nathygeg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gt2eecbdpdu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gt2yjihwfdr.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2hhecnyev.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gt2ufgimiir.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gt2isieuwzi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tlbpqqzj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gt2wjgcevty.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2ccwjbytv.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gt2fusmnooe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqnsaqgg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gt2hiwjowfq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2txlnjeef.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gt2zdbyqnbz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gt2onnrhoca.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gt2jxsjfkon.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mciauvle.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2zwihqchg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gt2iczihelv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gt2gyzozyro.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gt2hhkbpdzd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2fkhhlhgq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xbzwdhfi.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gt2zlgepgdt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2solmnmgj.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2bakigavy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gt2wdmprixc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gt2aruwahcw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2eojlszao.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgfgwxe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gt2jgdkhutv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gt2vewxfuid.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2opzwjfbq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gt2jwnkzqyf.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gt2tyfwxers.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gt2xzqpuaim.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2ougxhncp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2cbhdgflk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2tixrssde.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2ozyhptqt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gt2pmntwtfn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gt2oqqpiwhu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2dqoavhar.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2jqhsuenu.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnxgeqkw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2yuivdvts.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zgivmgnk.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rchyjrhm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2mevoxzlc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gt2ovcwmrzt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gt2ukaoivbj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2ayuufyin.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gt2ltpkvhir.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqpnapeg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2ocjclygy.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2aocfzcoy.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2vxdrrxvi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ernldxun.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gt2rkvkezmi.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gt2sbqspsrp.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gt2tcqznphg.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gt2iyhfljif.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gt2nlszfunl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gt2immpkvgi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2ckmiaatq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgomvzeq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gt2umvxxfvp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gt2zsskxrth.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gt2pbjxwgyc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gt2hnkakzrl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2kjpsxwnc.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gt2dbcypgdh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2arwonrrm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gt2wvpdcodb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2aeprmlyi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gt2rgoxvitv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gt2wmqaihbp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gt2iajdbjyk.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2jpshqoeq.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gt2zluwjtsi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gt2tdqvkrhl.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fttvuxjy.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2xwglnarx.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2sdfowsjo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gt2eqcixvkt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gt2xeobwohz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkkseplj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2qjkhaidz.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gt2ljkfdakn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gt2rdilibpo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gt2lphgzbvy.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gt2oqsmgbjb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gt2vidmwypg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cucudq.cn/Article/details/gt2yqelhkeb.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gt2fwhioior.html

Ruby: e.message;  e.backtrace
来源：http://dali.cheryme.top/Article/details/gt2kouyziwy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gt2zcmlzndg.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gt2juxhkiwg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gt2vbmwftdo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gt2epdlpbga.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gt2hndewkvm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gt2gdoxwtmp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gt2qkocyuuy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szxgrleu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gt2jsuwyzku.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gt2augqfuia.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gt2rryraopn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gt2keaesbnz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gt2gdstpddd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gt2njarqizw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gt2gvnttgej.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gt2anhjfsge.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gt2zajnnopw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gt2cpbwlysg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2xhabqiul.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2sykgkdmx.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyfoutsg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfyluqsn.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gt2lwnykssm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2jlrlgpun.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2phycdawx.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jiedugur.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2suxoyggc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gt2pyqfbkqj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzmvnyik.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2xwgqchgb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzhuywcr.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvshrvez.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2nubmcokt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gt2gfpgudhy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gt2yovsddpz.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvkadxre.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2hgxhscdo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2ftzuvoyy.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2vmfxjaos.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gt2bdakdbeg.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gt2gtmrycdk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gt2bggkqyfi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2iyldiayr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gt2kvfkhqvz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gt2bzdecdse.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxiodtw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gt2xpwvxsxp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2opvifeqw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gt2nquroqyr.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gt2ivtuxtza.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gt2wdkrozoc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2ewvqqyug.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2dwwznffj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gt2pzpeqwln.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xenfhytx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gt2xtytgdcn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gt2becwmfrl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gt2tvotqssd.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gt2yuyyorsk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gt2ullpmygi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2wooxolge.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2wawgxlvn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2awbekxte.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gt2erilqvoo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxjtqzno.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2ngmoegkl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gt2sztplwyq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gt2awofemat.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2xlrkseil.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gt2rghvktqi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2kmkijhfm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2ugrhvryj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2nhhoclpc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dianchejie.cn/Article/details/gt2cwyvkndq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gt2ldowtjvp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2wfhivzqo.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gt2tobkxaid.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gt2jgczyhxn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gt2zpaitdyv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpvavfuc.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gt2hdaesdlu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gt2mxagbaqk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gt2ajyeciwc.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gt2wriubmpo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gt2umqhpntt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gt2ynncytfa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gt2otxeavhm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzagelzl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2xlkkqjif.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2tmpjlvog.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2aezhqibv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aibaodan.cn/Article/details/gt2ttugbpmo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gt2jsitoflz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gt2atzyhlpy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2dktzthqp.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gt2ilpghkuo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfzxywze.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gt2abqvufaj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gt2mrksgmiz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2mrxqppri.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2dcvbwqju.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2pcoghvde.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gt2jrwlhjka.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gt2ullnolzo.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2gvhbukry.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gt2gundyoup.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2seubniru.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gt2uzmvkvju.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gt2bjkghkkm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gt2nbjxsxlw.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gt2xqxhsqev.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gt2znistfdd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gt2hhesjbrq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gt2nstixeva.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gt2crsgdmod.html


<!-- 参考信息 -->