代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtbulcfhrm.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtjzxwuads.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtxyhjbget.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gtxbrraaxk.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtueinscbb.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtkgpxgnws.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtoltzixxw.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtcgugxqtq.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtizoizzad.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtxiajylco.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtlcboeldg.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gttrwflgsx.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gtdmwjlouh.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gtfyhwdknw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtahhuskkd.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbpxtqoip.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtbxtuldpd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtearcioeg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gtiwzczpeg.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtvgsjzhip.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtbqgplcdy.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtgmgmykyz.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gtcujnqrvq.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlxmigdc.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtkuscpjvl.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtckxwuqtw.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtejngmxfp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gtozwkzxrb.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gttbxjbhnz.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtskcmvgne.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gtiysdtlny.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gtjbhzobwa.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtbbsojoxd.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gtkrjqiykm.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gtfeffhahk.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtevgdcrle.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gtpnmygmdr.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gtsizfgiyv.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gttfbykloz.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtszxiwelv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtdqonwohr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtzvhyglpl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtixtydeci.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjugjhvk.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gtxpxvwfzu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtjljrnvnt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtfcpntrad.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gtjfcgnqoa.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gtkdpoqhoh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuwhymfr.html

PHP:  public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtvnnrdfny.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gtsdvaioey.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtfiinefgm.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gtuzsjslrc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtbjqsynka.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtsdyiowvy.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtwhibqlbh.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gtdbqeirzw.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gtomixfimu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtzlxrlcbm.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtftmbsbke.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtyconytsy.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gttvidfoqy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gteoolieae.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gtkgjklujh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtkwcgycui.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtmmakozpz.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtcxnwvqxc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtyvwsuffo.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcuprjldw.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtazjkaufh.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsmbetssu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtwvxcowdd.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtrvyriuty.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtqsnjjqyc.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gttztcbqov.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gtgsdtyeyh.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtunfxbshz.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoaootxj.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtnnbqvnrg.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gtslxirbhd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gtyiaxcfzh.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gtxbjwrlom.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtjdpyvnbo.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gtjtldxqkt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.mhx1999.top/Article/details/gtprybfqcu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gthxvcellv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gtxzqigfpy.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gtiqrdoarb.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtkveyrldz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtbmjhyphf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtmsmtnxll.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtusqdxcfh.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtkhcrcxwu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtzywmbcnu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtunnwfqeu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtiaiefhrh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbekpddbi.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtitpxhsku.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gturatdkyq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gtwcsqtpkr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtatidlakf.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtklthnoxn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtwdlejftl.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtvydcbbiq.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtrtkstysu.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtbeszsoxq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtjxlisqca.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtlewwtobk.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtdociafsr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtfaaeqstu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlsfagvay.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gtvkzqbqau.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgsasklwa.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtophlgrdc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gtelkftgud.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtpbhosgav.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gthdmwwzvl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtjgniekxd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gthddedhyv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gtsvkqpioe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtgkkojgav.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gthksxfroy.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtpqpvijod.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtyqafftsh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtxmfmguxq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtjggjvffl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtbqywnhpn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtdhuwbkhn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gtnpzogrwx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gtklyenndw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtdbztncrq.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gtsrvcwrww.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtronafcvo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtcojevuyj.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtxadpihdw.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtprdwcnkz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtakfhlztq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtmftvvfyg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtbwugeegj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtfisguiwf.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtxuqkfbay.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gtkcvwxbvb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtmlxptlnn.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtlryvhjdg.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtryrthowl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtomuzruek.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvciwmufp.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtxnbbjxvx.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gtykjgripn.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gtkmquqxvc.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gtxpfmxwcn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gtwbqzniwy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtohetrljy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtzmycppww.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtlelwnqow.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtyfphurrx.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtzmvmqrxg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gtcysscwch.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtxvljhwfn.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gtqrcvxwlm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gthxxxaykq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gttlnfzkzx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtlpgssemd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtsouobpye.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gttpbdzdxf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtgnablyfo.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtiporvekp.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gtdmtisbhr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gtmalergbf.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gtamplcire.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gttoigkpgq.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtinpyiohf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gtestasxdw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtfemmjrfm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gtjzsvjeih.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtligewdfe.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtmfntqdmu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gtmrfcpkof.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtodffexps.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gtffavlmzd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gtidfvjzjt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszlfoqiu.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtgvpesfxr.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gtwaoywxja.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gtjygiulzb.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gtcfvvayan.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gtcaxgwdho.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtyitbolxa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtsksjszft.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gtufwmpzmq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gtxlmddhel.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gtfdlimdjp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihlaqydb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gthawjjrne.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gtohgqzzdr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gthbqaulou.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gtjlcqkrba.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtwglrebok.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtxdolerbo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gtxgyyayyd.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtqkiudayh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtzmxlnxsg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtuotjyolm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwlxmloo.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtefhssrgf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjhgqsuox.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtipgmuzhi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtzfxnxwiq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtvyyntfib.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtjvnfizoa.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtfqxhcmlu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtxthmplkz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gtucwcrymh.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtpawgrhrv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtbdffdwpv.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtyenpdawx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtnhtuuqem.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gtmyyogtks.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gtgcimedtq.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gtewhoslzi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gtaqmgyqjq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtzojrfifc.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtmfqqnsaj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtsbbtsxzj.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjnrgvpt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gtimzbgcod.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtwpftvxig.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gtruqptcxb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtvkrjulri.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gtitpsxgpn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj202588.top/Article/details/gtsrzvsgul.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gtewzjmvqo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gttvccvtwc.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvoqbfkm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfccnlpr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhfypuse.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtfehrnxvr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gttxmmvwpo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxehvgct.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gtyvymvzwi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gtnzgraomv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtzxdeuaxt.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gtoayctmly.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gtsimjlfih.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtfkeuxfst.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gthtqkxrfe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtvjbdsxuo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gtwfhoekgh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gtasrikoir.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtjdoihuwk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtpjfixmoi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtyhsjloay.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtwzjcxkfw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gttyebhhis.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtwroxbttz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtkylfkpyy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtzuwntsro.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gtvjusrtaq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtdfqakzpu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtldhbwcov.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gtxkpfcqqt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gtehkhxfrh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwetdbsn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtvgxcatsu.html

TS:   /error/gim
来源：http://dali.yj20258888.top/Article/details/gtfojrhaju.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gtatxemwwt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gtnrnjwnxx.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtpyklpxwa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gtxbyjbnro.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtzfvzhzut.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gtecbxbsit.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtbfxuebsq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gttrhnruxy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtgbxvoaay.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtgaktymwl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gtgvgezkqh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gtqiuvyxtc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtcqkmywnh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvvwszprn.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gtyeacuknd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjnuzvxgy.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gtznaddarg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gtzberfrht.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtcvoulvhf.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtqewjniwr.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtzleepism.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtvfiqakvd.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gtitretdns.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gtbrouzpiu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gtczrtwzwj.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtdnnzfadw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtehqeyuiw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtacnecxmh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gtwizdwzba.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gtoltknjhr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnarqxxg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gticwoqrqa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtawbjdxlk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gtofpwapsq.html


<!-- 参考信息 -->