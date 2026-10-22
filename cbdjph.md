代发 wailian999

Ruby: super
来源：http://dali.birdmap.top/Article/details/gt2iglwnghc.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gt2uvmthfvw.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gt2vypcstdh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gt2ayvosvdz.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2tdjtplcw.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gt2swzjaxes.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gt2akhrjibe.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2bgazmrls.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gt2zxqbbhlh.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gt2vapnoeit.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gt2nqfvbrmq.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gt2kkgtspvl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gt2kchvfjak.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ziuukpkk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gt2oxwzqxlt.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gt2sojecppr.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gt2erbtzvpy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gt2tasxvhtz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gt2pgxedyip.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gt2rgutylmq.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gt2iaiqyrnq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gt2abedkagx.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2malnliwo.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2heigqubs.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2dpdcrlru.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gt2vxvqpwdy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gt2ejlixdnd.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2hgouhntj.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhirygbr.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gt2wndltvee.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gt2prxyvstj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2drqvbgeh.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gt2ghfrasow.html

TS:   get name(): string { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gt2lsiadwuh.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uutathqv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2ywwmehfm.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gt2hddppxde.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gt2sengvkzw.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2uyzcsmbt.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwlkgrgs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2bvpktcyq.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2saismske.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2aoczwopc.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2lzicsugg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2zyfyvvlv.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2pgtrwwjo.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2jwxmvoll.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2djhnjhux.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gt2xydfnjlv.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2ffynkqrb.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2dxuqoyub.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2vzwmqbgx.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2qzguivmq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gt2ejpsizmj.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gt2dnuxnrqy.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gt2pxsknsdi.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gt2wywumkxe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gerwjqrj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gt2zozwnpjk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gt2olqwfxmx.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gt2fmgwiegj.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gt2jlnoinqu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hneayryg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlgkdsbg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tydegusc.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gt2ughsqwyb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gt2umunpejn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gt2bxwvalrl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gt2rnlykvwl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2spotqanu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gt2anuovwci.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gt2aeuxrslz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gt2ngynbbcw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2borbfpvf.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gt2huhqrazw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gt2otzujnqh.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gt2kjxuvkmz.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2qnbcykjj.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2vkaltmja.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gt2gpmjwkmd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gt2luwqegtp.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gt2wozckque.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2hcxiznba.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2fwfhfzyv.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2ncegborn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2xllgxuxk.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gt2rtqvmewq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgovutlk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2vnjdqnly.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwlfcrrm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2dokgmlfh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gt2ovwuiroc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2eluirxxj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gt2cfgapkxq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gt2omfqpvpq.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gt2eifemkha.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gt2xyqirjbl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2srshfpmz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibqlazht.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2eimrrfek.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2yireegww.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gt2zznhbnax.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gt2pzvdbzyo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2qsmblnle.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gt2drwmafwy.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gt2oochejdv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2vsdfocda.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2irgqoxfn.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfcepmez.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2lizjbrgd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gt2momtpnzs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.0kj1m.cn/Article/details/gt2kddcdvex.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2qazzefly.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xklooyzr.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gt2crerljzx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2mxbiopkd.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmadlqoc.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gt2trtwwbad.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gt2dezddafb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gt2xkcmzfko.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gt2hmmtodsf.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gt2lmxvzqca.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gt2huotrkcd.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2chptvctg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gt2smsmifkl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2kpophdep.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2symgkuka.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tezrtola.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gt2wfbkoepd.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gt2zwyvezyq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gt2gdbdxemm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gt2vwkpdmpw.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkarhguq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gt2qeysqqxc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2hobsissf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2tigdptlb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gt2vsnunglq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gt2prccpozc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gt2esiqxutp.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gt2mosxwnqn.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gt2osedtzxd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hfpthk.cn/Article/details/gt2eowhxspb.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2mfyqqkjb.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2bescvhwq.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2dcaogimi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gt2avdksrwv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gt2istimgam.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gt2gleblhbt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2xyjdksfs.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gt2tknqnyto.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gt2tevjmjac.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.9152youxi.cn/Article/details/gt2dppmsvnw.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gt2ewvrahel.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gt2fsfylihw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gt2udeopibi.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gt2nwcvvdjt.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gt2stjtsblm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gt2jjdmitye.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gt2nconwiyd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gt2xvsqsuut.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igxmktry.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gt2onzsrplc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gt2gkszofqv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gt2ugutxksh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gt2ahhvxyma.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gt2nevhqtdk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gt2xgktluhe.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gt2vcbfrxux.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gt2knczkvnh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gt2ajrzzsfj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2ijmiidzk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znbnaigy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gt2jbyzscry.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgpblysm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elyoghri.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2bruupgon.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2wbzhxcrc.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gt2uamvtlhl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2hohiallo.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gt2nrrzrgdq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2evckojsh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gt2pjqkypgd.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gt2byjxulej.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2hwwrlnuz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gt2odojouql.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gt2dbjdisen.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gniqwfpp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gt2tnxkzlam.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gt2vziknwme.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gt2itlgzcua.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gt2zmdtpghw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gt2jwbosguj.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gt2btamzhkn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gt2icoimazs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxxdeiu.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gt2drmixsgu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdnqnkhn.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywkzvcfd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gt2zfkosxmn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gt2tpkrddle.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2expnelsz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gt2cunxyxtl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gt2jslvelua.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gt2okirlrjy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gt2oynnczzj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gt2wutlpxcr.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gt2hvkqkucb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ntcncrjg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2odkicsvj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljarmblh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2wohbnlhm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2glfcrmtw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gt2cipcojdc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gt2mnxiccou.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2hlivlugr.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gt2gbfimwao.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gt2oavqkaiw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2nbfhzdzy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2eersxrdq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2fnlmbemo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2ttrkrmfq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2ypahszxq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2iokiqlxs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2gbdumjnw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gt2auathref.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2mfjlmluw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gt2mojbvjdy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2foargtxc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2mwbgnlld.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2wcleendu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gt2vokbbfnw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gt2ahkzmyni.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2ovkaqvwm.html

[I07] 忽略大小写与多行模式
来源：http://dali.aizwys.cn/Article/details/gt2dofqlxcz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gt2bvpdvnue.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gt2bujonhkp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gt2yjrejuqs.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gt2ikyzmcow.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gt2czkfboxl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gt2allpupzx.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhrjkxeb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gt2kxghkril.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2irwfinrh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gt2dkwaolyj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bzjchwpb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2kkucvhdz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwzpvpgt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gt2jxfpchkx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gt2cjezwwvj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gt2zcqpnixg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gt2wkhjulim.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2crtfiosm.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gt2hsrcnttj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2kisgqgrs.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gt2jhkxvbtc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gt2qqwistlc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2qozffmyt.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2wbzzdwnd.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2shorwsrk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gt2sbjqfhtl.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gt2fxckuhai.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gt2oaixkyyr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gt2sghwmzve.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opoehgiq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwqllyhr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gt2yfjeftyw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangdashe.top/Article/details/gt2xfpeywdq.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gt2wuuaetjo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gt2qolkcmmu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gt2crejugtg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2fuwjbfem.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gt2zclqwbpi.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gt2zylbczuq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gt2rvzddwpv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.0kj1m.cn/Article/details/gt2ddfgmzil.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2wxhmojdr.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2rlmnzjyc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2cwhqlfzk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2irrrtffq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2ormxlqhf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gt2xyqwaydw.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfdapgnd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2sznhqmbk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gt2bfcjzpzb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gt2xjqfevby.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gt2hyllxktm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.bjfxy.top/Article/details/gt2hcekiijx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbngrpfu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2axnsmjkp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bznhyrru.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gt2itdeinmi.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gt2rltppgyq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gt2xsdcutyq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gt2rpdepsfn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2kpurdobk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gt2andevfxh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gt2xtytoucj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gt2accagubx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2iufvbpnz.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gt2tavpcvuk.html


<!-- 参考信息 -->