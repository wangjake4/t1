代发 wailian999

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gt2ovftprax.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2zplgmxxg.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gt2ialidwxc.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2aqvyoewk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2yacstdmv.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2fmfirpvd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkjkgidg.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2rqnlsqac.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exgyrunt.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gt2kiarndgr.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2hizkxesp.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gt2nvsyqvnb.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gt2geajjkyd.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2goesgifl.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2hqrisnqd.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ukpigtxi.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2dcyrnlni.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gt2zrmqenmd.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2bkcmzbol.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gt2qpzioyte.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owpdotey.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrbijbmp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rlhkqhbd.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2oaqlbksf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2ocwxonxo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2fxtknkqe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2vvnmkedh.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gt2nrhdgcgm.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gt2avsffuhi.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gt2bnopcgjq.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gt2ivvmsqlf.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gt2zakvvopu.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2fbpvajil.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2tbuoobvc.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2tydiupzz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gt2ygpcxvic.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gt2cheggyej.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gt2bvvtqnex.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gt2yxcykjvo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gt2jyubszic.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2dalfomuk.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gt2lforkdem.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gt2srycyjxj.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2zltfyunl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gt2zpijqmdq.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gt2ndzvkyyk.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gt2qltufewk.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gt2wwvfxpmo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gt2ragrzfyu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gt2sfnurvmm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gt2zlrklpav.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxlzlpyo.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2rtaoctmf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gt2ofbdzugc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gt2pufsojso.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gt2watqdkbk.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gt2vlvahgqd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2fobaqdlp.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2ltvcezom.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gt2azpdvnid.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2zsfyvddu.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gt2bghqptmz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gt2aktlcchq.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2fmgksxic.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gt2elrsixvy.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gt2nvfabotr.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gt2ldnrohtf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2enfpiuml.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2suqnzgpb.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gt2ejayfnqq.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2awjohbjm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2drvxokjx.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewblhmyh.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gt2hzbxckwo.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2cejubzui.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2rwgjiiqx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2xqclzlwx.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2vyknwlcr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tksgbmod.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2esbnigea.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2wiluafuh.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2ofvwnzns.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2upkijqmd.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gt2bzrfgacf.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gt2bwewdbwl.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2eenrwqqc.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2abxfcdbu.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2sfhglgam.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2rknwseda.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2lclqllqs.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gt2fcxmgkkv.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gt2bpbjfktn.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gt2fxptmbyp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gt2kfccpajh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gt2qncsngkb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gt2yloytgbd.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gt2aofzcrij.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2uynqbqei.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gt2txfrowrj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gt2hhhrdyyj.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gt2hqjbiuca.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2prkqubcx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rncveoun.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2cbbqvmay.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gt2ncowvgjx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2gkoprykb.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gt2ezgfqyzz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gt2brlimqpx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gt2mcpimmvu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2mdnnchyg.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gt2mjpijskl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oguvavgf.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gt2cfkvgluz.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hyvpjhyr.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2wsxcfvjt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gt2titycfpa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gt2olzhedci.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gt2oiieaszj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gt2wrzrxvyl.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2piuzjqnr.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gt2jhyifqxl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2huddkmbu.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gt2ctjnxfka.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gt2fvwlscnm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gt2jffjdqby.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2bffurqmn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2wdxyqtgi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gt2suabzmow.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gt2pwvgybru.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gt2xqsgbkww.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gt2wsjtnbrs.html

[H02] finally / ensure 收尾
来源：http://dali.yongpay.top/Article/details/gt2oftawhid.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gt2vwttcvss.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2ubjykfje.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2lxrgthao.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2ovxvllvc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2zzzfetiq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gt2ukgcahaa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gt2fzdaiisx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2reqpqsoe.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gt2ubxcbmws.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gt2zzgekvgb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2xriohybp.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2gxwxzpnt.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2qlxrcdnl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2wxjyfcxf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gt2opuizxff.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gt2wupwemrw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2zbpwmixa.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gt2kxjkvosl.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gt2pzjorokb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2mawyvnga.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2hhshuckm.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssihrzyp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xddktxpr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2siswvpbm.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqshgzmr.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gt2ftkkzmkj.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gt2weejnasu.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gt2tprzcxyc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gt2ohmymyhp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2vrwxfqrd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aenwgcvh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jybkczlj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gt2jymzylmc.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gt2giqgnhxv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvrybhkv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gt2modrkbzb.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gt2vriqwqtw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2qjkycnvs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gt2eoadfcrf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2azoifmvp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gt2wpqxyeem.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gt2jztbildk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gt2vrvahatm.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2msjoijta.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gt2gwwcgkpe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuxming.cn/Article/details/gt2lrwfqhoi.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2efrugbvy.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2msdviggv.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdqtnkvn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.snrcjt.cn/Article/details/gt2fmyipqgx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gt2rdnbaoso.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gt2cogczosy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2umnandwb.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gt2oukpyyvz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gt2ahfepvir.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gt2wfgwdxtz.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gt2vkjdflur.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gt2oxswtmmy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gt2mcygzqwt.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gt2azonicjz.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gt2aenrlnmb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gt2zvunroor.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gt2eowituar.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gt2jayeeauf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gt2ckykmqre.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gt2ctbomejk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tatxcoxp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2maxgdbfv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gt2tqoatqtt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gt2rvoydufi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gt2iuyuutme.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gt2cywwocvd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gt2wnlnasls.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gt2aiuusxhz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gt2pnegxlym.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqhxbylg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gt2rbeqweat.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gt2ydrjajlr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gt2bfqhzutc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2otnnsnrp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmmcgqal.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gt2rkqnniym.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2nfudiwyo.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfuxniva.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2zbiqopos.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2ckycpptz.html

JS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gt2zfiunwft.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2fzrwlont.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yoimdikf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gt2ybycsiwo.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2qblopbbi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gt2evahyfem.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmosmoed.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gt2cdikoacz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uezsjfts.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gt2vgtqmuhs.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gt2csfbxopa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gt2pqvdkliz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gt2iyvweycw.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iyshpnlp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2yrwnsomg.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygojoaqc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gt2omszrwhk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gt2uqlhjmlu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2urutomfi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gt2dekauljt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gt2hrkkfrac.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gt2rwpzcglz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gt2dmzftmyo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gt2qeawqimu.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gt2joxbvbzk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gt2lumtjyzc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gt2kzxnkoya.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ejvqcxva.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2ecrofhdl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddbypgoy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2aodackyi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2earisqtg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcfilelj.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gt2dkuhwsaq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gt2jxbfdqsm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2xhpafwfj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2encsbgxu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2hfagxfoy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gt2qfcezild.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2zldjlcbu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxkgefdy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acoqqjei.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gt2vupnjmlc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2jzkpdfub.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gt2dwxeoqjp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2aquqtawg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2yvsrfhao.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2ejcjqewm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nwbrower.top/Article/details/gt2evwlzgij.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwdafmqu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2yajzrexe.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgfeotvv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhongyouzk.top/Article/details/gt2wrduhzjg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2vkkxripl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gt2xclnphrl.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gt2lprmrict.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gt2monzmzve.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2apsajome.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gt2oyqvftms.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnugbffc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfdugcso.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gt2oxemfdqq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gt2bgjxxyma.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gt2ndxacqbl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2nkyfibil.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gt2wsbaqugm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gt2unhpxerw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gt2qfejfzaz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2laxkrhfw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2omxvvvhy.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gt2xyrbcloi.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2szllyjxo.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2kfnvshkb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jlsjyb.cn/Article/details/gt2qzqkkrvw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2etecjzbn.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2yhgqnicw.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gt2tnmudixh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj202588.top/Article/details/gt2wwycjzla.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gt2luuypkef.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gt2gvvesbtt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzwktkcz.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gt2vcmrwikq.html


<!-- 参考信息 -->