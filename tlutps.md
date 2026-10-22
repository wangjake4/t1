代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gtxczvwccq.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtjaqlojie.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtmxhovyup.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gtmsxlrhkh.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gthascrwxl.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtzhgheljw.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtcoepmztx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtqiloitvh.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtybaycoyq.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gtsudxhoqq.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtnbqemthk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtaqnaoesx.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtxpeenkpf.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtwgelipen.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gthvzkoinx.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtxebmhkso.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtujinkpkx.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gtzwnfvkvi.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcjzpfmms.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtwsqnvdjd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtcpsxhoij.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gthgvqjkhc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtpkjghnlq.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gtfwphlkkb.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtbryqmrls.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gtzeyrewfg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjdwcoib.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gthyeeflsi.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gtowxgllyc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gtbpttsskh.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtzdlkdzjj.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtjzswzsrr.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtaugxyene.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gtfollwgnb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtzcchgoqv.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtzreumcte.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gtmcywtkpc.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlkxvbqh.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gttssrruht.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtchmtdsvt.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gttnfgfrzw.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtgipdudlr.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtzkufvrwr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtjmaraamy.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gtsfpqpwtv.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gthenhaxyb.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gtrzyugpel.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gthrtaanal.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtximvdaif.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtuezmfhbw.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtyyqmnbgw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtqyxxyyde.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtlnbexbws.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtgrreoglu.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzykbnlcu.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtqafgnpgu.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gtvmbmxnhv.html

PHP:  $u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtrderzrqz.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtmwyhhwnx.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtnjxofnkt.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtsshchfrv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtfahiaquc.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtumypfbnv.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtqxsyazvj.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gtwwwsusoi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtpeumbgvj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gtlyvchhqa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gttfhmqmwa.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gthfservjp.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsqjacrh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gtaelctpin.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtkfflagtv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpafigyqo.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gtgnidjxta.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gthdhtbown.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gteqffogvt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gtqifyighw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtgfwpyoeh.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gthshxjjcq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gtnnabeiyh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gtoeyhyjxi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtjekymwhf.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gteauromtf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtgoazrpbm.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtsmnofxgt.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtuaathtgx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtjqzyhvcq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtzahwpkph.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtwibewhpu.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtttnqhojo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtagzkmcfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsbrercyv.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtecurcbbe.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtncgrznbn.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtoscvejzf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtvxcwnnfy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gtitbtvshy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtgurihzyi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtpyayvjyf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gtmxgtkszp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtofyorxix.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gtgnmdtosn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtczfhrtpn.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtmsrtnnfx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtiweydnvk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtiddhcnkp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevowcbgo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtxhcgwynk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtabfcefup.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gtftsxyrjs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gtsrdxadjb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gthgxbhqnf.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gtirwxwtwd.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijgzmotx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtqlwylbfb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gttnsimxyi.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtgywkcsjc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyvnyzqg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtnzxglkrv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gtgoitgajo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtcuafwhiz.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gtzqjpdeox.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtimybiclw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtrhatounl.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtpznclrrb.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtsepnpgju.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtyejlibke.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtmcblequf.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gtcersllmp.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gtiyfgkyve.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gtzoqirxbt.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gtnqltmzsr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gtbdvmyvks.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtsenlzwax.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtfmhimoig.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gtigjxoqse.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gtnqscsgme.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldajtflg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtafrrkovh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gthpwmfxab.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisxjqral.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtkkmhrpxr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gttnbbudpn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtqzregqoa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gtxrugywlq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gtjvpywudu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgncgsspr.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gtppjvbeat.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gtnbljkbkc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzahftti.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtccxnfojh.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtvkbeunao.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtjalysfrs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtriorwlmj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhmtomqe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gtuddfovxp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtlyrmhfel.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtujrrbqhy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gtwbzbeqef.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gtwajlkaqy.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gthfpjzlit.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtsyeirhpf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gtvjuruhwd.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtisgihucn.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtogefitll.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtmyjeqieo.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gtypnpkljv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gtyxwztnir.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gtavaomzey.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gtgshmtris.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gtwtgnrrwn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gtohsgiefg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtblztyeek.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gtommtnklm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtcxmbpryp.html

[H10] 资源自动释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzeihmisb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gtqadpeyrj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtowzqepxl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtoyluootp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtxyprgbsp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtzinmtkjg.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gtgplecmlo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gtypsrwekq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymfhnqlz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtcrbxddoo.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtmxiiutyv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgmexakbb.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtcowgsmbq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtxilpuhsl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gthfhhzmeg.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtulfkhkax.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtjjycvnmt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gtfrjxfxad.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gtzbavnjre.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtlmlwmkzx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyucicow.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkyfykbx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gttdlymtyv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaydgbuji.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtjwqdksqo.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshahhdjp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjbdyylm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gttwqgyryj.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtdqkufwfc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtukfbutwa.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gtrickvjlr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gtbefqsrey.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cdnleiting.top/Article/details/gtjgvjkbxb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gtsmruuhgd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gtbvnljsfl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtphahaows.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gtcrebtgrz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gttdqrxrhp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtlyditmec.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtniywviop.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gtgrzmulep.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtsrrskjwd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtwpwgfwaa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtqstyeeht.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtatblgcji.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtyrnjlnhv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gtwblfqbhs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtpsrtawtn.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtawiljeod.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgfaopdi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtficqsfld.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtokgberup.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtcpmjwlce.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gtjjkzdvyf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtzitnaswf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtolusbrxn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtzjsnxztm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtmjexdqey.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtxrzrhvco.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtrucmujuf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhvhwwmd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtihrczwxe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtvphdmulg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtzwjudxof.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gtthoywbeb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtarbpekmj.html

[I07] 忽略大小写与多行模式
来源：http://dali.gzhubu.top/Article/details/gtsofvjqqk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gthjemmdyk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtmrqjukeb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtodougzay.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gtrgudoxvw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gtefatxbmt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtmjukdntx.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtjyglrmci.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gtrpnzckvn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtloxviyxl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gtuopsvmew.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtcibiidgx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gttsabhruq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gthhcnrggg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtihngacrr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gttvelsvnl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtyhgoyjrn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtfkzzcksm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdvtexvqq.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gtvfikcycl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlztnrvug.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtlcfpzydk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gtkwtukeco.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtvajnupzy.html

JS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtyeoznotk.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtrqxegnqg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtipnmlzod.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtleszmrqh.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtwishoztl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gttjmyjmzg.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gtspivmcua.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtofctslgu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gthnstocmb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gtnqzzgpit.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtgrtlszkz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.quarkkingdee.top/Article/details/gtsyxvtwxm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtjfcgfqzk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtxssflmnx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtpwawfmvo.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gtixgkoeor.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gtndswremw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gttpuodhsv.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtrztiuhac.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtwwrwnqzl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtzvwxwejp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtqevhyago.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtygokdsjm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtycuaghwk.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gtmxnkfsmy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtonhhypve.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gthdgclmgy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gtnruvejnm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gtzvwehvou.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtrdabrjpc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gtviefrzqz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtpfxbqkdu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gthzllcohz.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gttysrgqbl.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtdbsknbhb.html


<!-- 参考信息 -->