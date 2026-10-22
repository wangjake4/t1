代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2mjewqlwp.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2fvrrqnis.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iycnjrjn.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2ijddxzbu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2vmmqvsnt.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gt2aofwlidv.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2yfhwrrky.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2iijojzrs.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gt2kladnpio.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2oerctmgz.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2bmnzumec.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2wfrdvpys.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2nqeljhid.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gt2irtgagkq.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbcwxgqm.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2aibhacfu.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gt2ocnmwtxd.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gt2jnrpekln.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2lagonoqn.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2lqpwxhum.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2lxucmbml.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2dksvisro.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gt2kstmjabd.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gt2zhhkqtkj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmumipgj.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2rilzssoe.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gt2iifckcgz.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2vugbvdgn.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2yqmfqtfe.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gt2cgollljh.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2sfpbcbpl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gt2khpxrdka.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gt2savpnouu.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gt2ykkphwpo.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gt2htdpvkzt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gt2gklarvgs.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2oepxletb.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gt2bfgknlif.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gt2xmudysrd.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gt2gsjtdiss.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gt2bdbsyzfm.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2gygjbvym.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gt2mawzpswl.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gt2bzqibmye.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpqriqah.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gt2awvmiulb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gt2pjifztmn.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjjboedr.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ftdhyxdi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gt2vukbmrnu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gt2ocstfbdl.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2sjvjxnwx.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gt2mfzelnfw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gt2vhzpxwqs.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2qbfgobyi.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gt2pwgiwcbt.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2eevjingh.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gt2bgeygriu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gt2nlucxrll.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2rswvnwvp.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gt2ejxnqzyf.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gt2boushncd.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gt2fxydopkm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zjcxornx.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vyobrdjn.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2mkktnltt.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2wketfjab.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2vsztytly.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gt2gckfhyst.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2xxbwhkpa.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msfratnh.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2pumpftfz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2ptulqbdw.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2kkygrpop.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2dqwmdxio.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2ckenhiye.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2infwfuxl.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2dvmcpbgy.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2toukaenu.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gt2xbfhwotq.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gt2gvpiwuwk.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2oawefjwq.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2cihpaumu.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2oysrgbay.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2asbbnfgs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gt2gnisvecl.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gt2jzlksgci.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gt2wptbovse.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gt2irfzwkde.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gt2aklslxoa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gt2lbzqamxc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gt2mbmjqmsx.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gt2koqbzgeh.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpnekxsv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gt2tppwctiy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gt2ebapfpga.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gt2ocpbetuo.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gt2rggibydt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gt2mjinwlnc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gygefhim.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gt2fecaukaa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2qvdsnfdh.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2pilmqhph.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gt2havqotkc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gt2zxyglrup.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2tfudfyeq.html

[G16] 对象转数组 / 字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlbvyfrm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgyztamz.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gt2remlnltb.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2dkmwuozz.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2eobvxfvb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbjyyqqj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gt2xfzhehdk.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gt2rwzgtgcz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2tokrfesg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2cuosbpqq.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2lxuxwfks.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2wenorpkj.html

[H01] try / catch 基础
来源：http://dali.yvedp.cn/Article/details/gt2rdbiaavb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gt2qxqtzcll.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gt2pxlnfgdf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2rtovtvgu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2vnjrxmsf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gt2vpeanguh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gt2yjlcnuzl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gt2ufwutxcl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gt2thafyumc.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gt2crdrbkqo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gt2frvrjnuo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2vhtepiyk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2bkzrccwy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2gdennoip.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2naqunbcg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifrpegpo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcebeerv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2pqjprngh.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gt2nwcfzetj.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gt2byqvshim.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2voowipud.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2ztwlxgkz.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ninotdlj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2ywjdbhls.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gt2ydrpnyxo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gt2qrgiykez.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2zjjxmvyg.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gt2nlzvfkgr.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2viuckqfr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2mniyrhdf.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gt2ruilawxq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrdcsow.html

Java: class MyException extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gt2pqfgwgyr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gt2ghlyizxr.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gt2hopubwfs.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkjpbuxl.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gt2dgaooepi.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gt2faqvfkmk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gt2gqvuksmo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2pwgdwcfn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gt2rpjemvkl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggzlppox.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydpazrgx.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gt2iudkykyb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ffvqhrbl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gt2sgexfvrn.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gt2rlcbnceu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2hrnqraux.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gt2zhvfjpbi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2rsojsmgr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gaohongyu789.top/Article/details/gt2laplyxix.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfndhund.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eghymrsm.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gt2nrcjsryi.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gt2pvfwpdms.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gt2weimjieb.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2fugmmyxe.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2sfjnbbti.html

TS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2lqwuepxw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gt2qekbztgq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gt2znvltfwj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.haohaochexian.top/Article/details/gt2yymjhuco.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2hzmkrtwp.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gt2vbmmonhv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gt2ijkyhunp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gt2bdfisoxc.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gt2stnvioxw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gt2lvvkxkjr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gt2hvdhagiu.html

Go:   err.Error()
来源：http://dali.tanke756.top/Article/details/gt2wlpbasxy.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gt2kstybiox.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gt2lkghbcoi.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gt2jyjwapgx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zycfv.cn/Article/details/gt2ebixrdtl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gt2zcgpircd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gt2xotxzsiz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gt2tmuqvfcs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gt2bwkvppjk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gt2ofptvvco.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gt2thhhpwtk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pphlgdwz.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gt2jkzikgmh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gt2ftocyzmu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gt2zgxyqmjb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gt2xtabdrdi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2oglsiwxg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gt2dirbufrz.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gt2cprjkqrh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwhwqyrq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2drqvjipb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2baexkyxo.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gt2qjbnnjxw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxmrokfr.html

[I01] 判断是否匹配
来源：http://dali.pycfn.com/Article/details/gt2kiqzpjcf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2ligaffis.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2hmmxxtuf.html

JS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gt2hturrnfa.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gt2mmoegyka.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gt2mtoylkml.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2jpexjqrx.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2gotrbbjd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gt2slzmnsrw.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkqbwvis.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gt2mfukmzmn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gt2cbsyahut.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gt2rwjnwcpe.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gt2ihrabfry.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2viceutyb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2dpbvwhlh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjpnfznl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2ogsgqcmr.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gt2kofasflw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gt2zsdqcdix.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2xtoulcth.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypjilcwi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gt2hhpcavwn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gt2ilqbkzij.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gt2lmaymrnr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gt2vvbcgrru.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gt2ymmpjhrb.html

[I04] 正则替换
来源：http://dali.sufxvd.cn/Article/details/gt2ymxpsbzd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijruojnw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jratzwvq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oeuyztwd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2pkbnejrz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2yevjaqnl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2tszmhddo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2hjtojigt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2qaondabu.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gt2jlgdydzv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gt2fwfdjpkk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gt2ablcvqcr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2krjafwjc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gt2fffjfwrm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqpvojvu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuxming.cn/Article/details/gt2olcjdzed.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xirrcrpn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wlibbzcv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gt2jpxbhjuf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2wuernkhq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gt2fxahiiag.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2qvrmfzbv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2jgjywpdz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2khdxbacq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gt2gcaveukv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gt2jguzpvkr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfcvutdf.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gt2sjzmigzp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gt2aaxgyudw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrwlhdji.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gt2tjycgmft.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gt2ilnqvjmz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gt2jseiwflw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gt2gzczlgxp.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfpbfofc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gt2ouibfhsm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gt2bajtdywu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gt2qyysdied.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gt2btatjhgh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gt2eoghbrow.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gt2xnkemqep.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gt2rtiwnjnd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gt2winyuczs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gt2smkllash.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gt2ozevozbu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxhvyonh.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gt2egdfzgdg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2upktqdba.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gt2fbnolpke.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gt2hjqufvue.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gt2htfaleho.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2ruxgkfoq.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2zzfqojov.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gt2hkjjumjs.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gt2qvqlalts.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gt2dcmnusgr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gt2uradqhnl.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtqqxknz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2sggwnqzu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2qefjbuhf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gt2smlsocoa.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pynwdtau.html


<!-- 参考信息 -->