代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2xdbgbokp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjceutmu.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gt2iinemapn.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gt2lnvshyyv.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gt2tyfgpgze.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2hdywaezu.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2juhlhnoo.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2emxhbcqc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vidkekce.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gt2dgothgpl.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qivuxooj.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zruhlsnl.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gt2bcwgbcis.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gt2qjbmxjfo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2iidonfhh.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xomkxsta.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2kxbsdisx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2svuxtjcx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gt2ykpeuxmx.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gt2ayvhdbuj.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gt2hlafglkc.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gt2hekrbfam.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gt2bfwczgcf.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2awaxrxpb.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyketcey.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2kzvbywkg.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2szixojfl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gt2mmvfnkdd.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gt2aiolllye.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gt2bvujbrfp.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gt2jnzqsyco.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gt2rbozfqwn.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gt2abpsbsvd.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2qzmryeuz.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2jftyoopt.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2nnqnvjlw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gt2coebchpu.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gt2arolxgvm.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gt2wdkfeizl.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gt2azlmxmxc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gt2zwfjtrxh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gt2wrgplnze.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfolyfru.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gt2rrvagxkb.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anzvtbmg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gt2ltkahrst.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gt2hjagosji.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2aqduwnlr.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gt2desolhnk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gt2dpyoxxiz.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfhipnlv.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gt2dsjjdslg.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2fhgblves.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gt2iolrcxhz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gt2izvqoiyh.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2opmtojtt.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2fonozfng.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gt2fvowibuy.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gt2ajvgxtms.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2wugxgzpr.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2mepuczpi.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qyapxiko.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2tmbleqgl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2knwwsvhr.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gt2jzfasgnw.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gt2hkgbjktx.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gt2yzagkgbb.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gt2hjbentik.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gt2xswkqkue.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2iuqakopg.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oynfpgjh.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2plweqnej.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2qtbifbty.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2txrtuufk.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2nbfkaqps.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gt2sjoxqxmw.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gt2vtalgfsz.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2lqgxipcu.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajkpdsfj.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2uytyjxjp.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2jnuscgfk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gt2bshufndn.html

Ruby: u.is_a?(User)
来源：http://dali.hfpthk.cn/Article/details/gt2caxagcfn.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gt2xtcejtid.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gt2fsstduea.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gt2hkupthiy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gt2amkqmiqj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gt2ydcykrdp.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gt2zigjdrxe.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gt2xavhpuzl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gt2nqvushgc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gt2pllcqipt.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gt2sdwyclsa.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gt2bhtzbbey.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2tjtekine.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gt2qsasxarv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gt2ojpedvkw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2tdainaku.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gt2qxvenwcg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gt2ssybokoc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gt2cvgjaitz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2eqhwwkfn.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gt2xxnywdih.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gt2yylwmlmb.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gt2dlwtblww.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2vpabjaxn.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2amfayuog.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntvjxzkm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gt2jvtvvlyu.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucvkdaal.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2akzuroal.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2lrrpgbuu.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2ehwnyvrr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2duvxmqla.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gt2abyyrndh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gt2isvhluye.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gt2rcieffpm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2vocicrhe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2ibfxaffo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gt2txzaxxck.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gt2xwipdbpe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gt2vdytzocq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gt2tlnaprjd.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gt2hfpvqxjz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gt2avxzadsi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2ygimqvwo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2kvslfkkf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2lofgcgeh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2glzrwvzd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxxpised.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gaohongyu789.top/Article/details/gt2jysvgkea.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tctwvsjd.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gt2qpbvhduy.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gt2jcmnmqlq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2ljwisigz.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2xfbshjmz.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2loadkxxn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2plfqxucu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rthciyuc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gt2fxvkdjwn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2bqxhmclb.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gt2qaqkdjio.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gt2ystyclhh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gt2syesrlvs.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2ilwdugsh.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gt2dfolkizz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gt2wvvdzlqj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gt2qcoskncg.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqpctgim.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2vprgpwgq.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gt2tzakrvqc.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gt2zxuseqjn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gt2bxrylrck.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2dnirheun.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gt2rchyqriy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krmkwsbo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gt2pjxpjuep.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gt2svzvopdd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gt2jahqugkz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gt2gnlmghfs.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gt2zccevoku.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gt2uyqcjhgx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2jwlvcuey.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlgvnrhu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rlrsfsvy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gt2jsmfxonh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2vpputyxb.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gt2lenvfhbc.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gt2rxyuguim.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gt2teodjvyt.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2yjeowptv.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2cngdrjkw.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2pzktpgvx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gt2jenfgeol.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gt2bftcvbca.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gt2phkrjuxw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2fbpyvfrt.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gt2hzkhzwpw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gt2eehgbdzx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gt2aalbnkzq.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gt2ycoaguut.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gt2drhfbdqp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gt2wyblysmc.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gt2utbtsbzy.html

Ruby: e.message;  e.backtrace
来源：http://dali.316326.xyz/Article/details/gt2dseennqk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gt2tyaqyevz.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gt2xjxhbddm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrdyfvc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gt2uxacmvlv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuxming.cn/Article/details/gt2bhowjfxc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohseftag.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gt2zochohfe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gt2wcodwgwy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gt2xliuvnrd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.smart0.xyz/Article/details/gt2jqosufjr.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gt2payfviyt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gt2gfuaexmo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2xndjnnwo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2cwefqcfr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2jseiefim.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gt2zoljfthw.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gt2pyrteamc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gt2qzlzrzqg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2tgzwquls.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hliurewu.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gt2atzqqloh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2mermpnoo.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2legmmuks.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2zffizvhn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2guracvmq.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gt2xcqwymex.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2difsyzes.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gt2bansjrfp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2oheuchwu.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2ctjeabfl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2wkuwyvuh.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gt2esympxwn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzimmymr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gt2uemmlbcd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzhujfjj.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gt2getsxhmb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2azftopjt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2mwmhbynh.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2jberupcm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2hlzwjswc.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gt2qfiouhdg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gt2ecqjqhdf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pepjqjdu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jximayzg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gt2gxofsfwc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gt2olyvjpgv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmlxlidp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gt2hdhxqxtc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gt2dhltlvvq.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gt2pzvlxusb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtpiolen.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gt2xoqackof.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2npujxgon.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2hhotghzp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gt2vnrhnpbz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2npwumvea.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2iarujjpu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2grhesbfc.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gt2rzvyovcw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ldsuxlju.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2zolkxiez.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2zrxfouic.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2xmclbazv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gt2zozglrko.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2ftkhollg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2yblpeopj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gt2uhggbmlj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gt2ptgextwn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2wlcmvoik.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gt2sbnrqdzd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2wqzeyiqb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gt2ouovkdrh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2kmzsetck.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gt2bsbmeodf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gt2ddpwtfen.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2jvhpgccg.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gt2cmlguptv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gt2aerdzfam.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gt2ejaiztqy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gt2wlaalimz.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gt2xhxadxql.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gt2udtvgnxb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gt2nftsjayn.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gt2ddsffbfu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gt2tijdrcgf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgfzy.top/Article/details/gt2zjpcsonh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gt2ypuhzxcz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytmtzojg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2grbstscp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gt2iyccsvle.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqajkufv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdltxlxh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pztqivlb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gt2gelnyoec.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2mknuvazg.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gt2nmovxict.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzqybdex.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gt2jtfvjrfm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gt2akwqarxy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2esdecybr.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gt2frrhlxhl.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gt2eqxydeml.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gt2wpvsbmhk.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gt2vhzrmvfb.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gt2gvsdmyiy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fengsongda.top/Article/details/gt2wkqfvqfx.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2nsgqobww.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2ehnuiuqc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2apjmvenh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gt2measbgpl.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gt2tyrmlqrg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncyycwbb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gt2gunsdaqm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gt2ngoevfvt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gt2hpmrxahn.html


<!-- 参考信息 -->