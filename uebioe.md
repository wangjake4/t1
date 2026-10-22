代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gt2zjthhdhl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gt2kiekvmzf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gt2mxnyokdv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2wnuiisdn.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gt2evmjjhte.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gt2sopxxzib.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzmfrdnx.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gt2rzxfuajl.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2voitkyod.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gt2hekbvrhg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gt2zhgvgevo.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2ybqrwfeg.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gt2stsdwuou.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2rksqchuf.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfttvrrk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2egsiwunb.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ybgmehlu.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gt2rnqqdunm.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2uownpjjw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2kemkyiar.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gt2adxegsqw.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gt2odkfxncz.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2splimkls.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2bkegqlbv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cydubdoe.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2kootmawn.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2vzvsfhvn.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tagmyiqj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2xygxhsbf.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gt2mwkuzooi.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2swdubpui.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gt2ohmzeiez.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wznnnotq.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvaghooo.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2mnotcqbk.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2cnxwhstz.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2pbxacrmy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gt2osufmxqx.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gt2chmirjyh.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gt2dswbdgyd.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gt2codbjtiq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqacqysh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gt2erdussqj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gt2fbgkxngy.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gt2fbciehbu.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxcerihq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gt2wqjjxzvu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gt2objbbnqh.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gt2bpizywxn.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gt2qzvkemhf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.0kj1m.cn/Article/details/gt2lqiilkov.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xvfgilbo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2dnabggvh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2bsnsrhrj.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gt2nwxqwipd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gt2jfoldeej.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gt2ulaejaiw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbiifbhi.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gt2pbpybkgz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gt2qmrtrowm.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gt2vlmlqkkx.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2wgkkcyep.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cphdoswb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gt2wqwuglkl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gt2kcpmlriz.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gt2otobsskr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2riucakfu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2dorewnut.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2bixwjzpu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2lqbfdkwo.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gt2uhwwoyys.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gt2gghfovjk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gt2fwjurydi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2lrkshqnm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2ioynobvy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gt2juxfuksw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gt2kykezxev.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gt2aveohbfw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utmsekxz.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gt2tryfwgfi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gt2ofywwkfa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2weswbnyb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2zvyrzpif.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2idjokmrc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdrdlrzq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gt2bvitooov.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gt2dzqmsmfc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovgubiag.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gt2icbpqswb.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvtezyxc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2mvquprjz.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2ehjmnqup.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2bsycgava.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2muymasmm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gt2fevvrspy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gt2uyqkjvry.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2nghcmqlv.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gt2kjulyteu.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2qlthdher.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2uprrgmoo.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2wfcudebv.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqgfwlak.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfpyycnu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gt2gddnkbsm.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gt2uiolvxhf.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gt2jpklcmqn.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gt2jknvqabi.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gt2xfotaxmf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxqsbmbd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gt2bgqlhssg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gt2vgxvbxsp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2bvtjccpg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gt2chppxcnm.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gt2sqsnbkfg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gt2txrpwanm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gt2jiqpyubj.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gt2asgjgzqt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gt2tzimsllh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gt2yaentrgo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2qtyhwzmz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2ejfmmnke.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gt2zywwtplc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gt2qmdwhrmr.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gt2gzgrvkuy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlbprgc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gt2sdlcylgx.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2cbovhepm.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2vdlreqkm.html

TS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2gdkyitrp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gt2feuaqqae.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gt2okldroqn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gt2xafboxru.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhcvlhhv.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2myadarnv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohwwryou.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajgcvdvz.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gt2qlfyvogb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2bmlpznry.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gt2omuhfjoe.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gt2wxawfcqd.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gt2sgpfrwdb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltargqpn.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggynrzvv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gt2ymmvnyzl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gt2tunfwqph.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ruiquqzr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akgrcdgx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmsoqijl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gt2yckqbirl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gt2jzpmxwdm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gt2zsjrmgjp.html

[H10] 资源自动释放
来源：http://dali.haohaochexian.top/Article/details/gt2zdizfbtx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gt2mknvxalh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gt2jevuinmr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gt2rpsacsoi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gt2uizuadjd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gt2vryahzqi.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gt2dhxletxe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gt2jgqpkmfo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2sbvrtcvg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2tbmvguig.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gt2uhbdnrnz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2hgenuhly.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gt2vlcblpkq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2ubpyimay.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2vhxadose.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2lnxqhwob.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gt2kqtjjvpi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gt2jjwuqqyj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gt2jrykaqrw.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrvgcxhb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gt2wusjhhqo.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2kszyjihn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2rwksaxff.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gt2tywgtlxn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2noahfaim.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gt2puxcnwmq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daxiang520.top/Article/details/gt2hfwbhfdz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2wagjrwit.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2pcbdcgmt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2tebhbucd.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbmabawj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gt2hibqhmil.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2lboxnofu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhnokfpp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gt2edtwnnyc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2lxfrfcak.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gt2etzdbgkz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gt2vwxtwgci.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gt2gpavahmy.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gt2vhfmrazk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gt2crrgytuh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gt2boouxoew.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2ggjldygk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2fdihgjkq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2fynhvuhi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2csnpygtx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2ldquopcc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gt2vvbblmoe.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gt2nrqgeltg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2pitkaivm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2oaxqwmaq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2ftkhzooi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2blhngavw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2zkhpykqp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oohxenak.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2rjolpctx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gt2xsngsyov.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gt2bhjvnlcz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2yhfpxkoh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gt2rrjbypuz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2awayhtjb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2enboadyc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2ibinldhn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gt2vexlcgja.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gt2mysfuzue.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ryaqqdrk.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gt2xzdmvtst.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gt2dwevxxdm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lsjolnqe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gt2lzcglvvh.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gt2czwvxtlx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gt2tiuszybr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zuwkcepq.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gt2mlqnjfbm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sweek.top/Article/details/gt2esnjubfa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gt2qsjguewp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gt2towkhcxb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gt2ynqtodyr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2ekdttfrj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2oevrgres.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcxaearn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gt2anzdvnjq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gt2woqmepmi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2bvigxydr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ufedtigi.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gt2euqxrzeb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wiqfpxrs.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gt2bqisjrkb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gt2acnpszym.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2itiexfda.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gt2nftsmgsq.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gt2jzwyvjtg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gt2hmwqtjtf.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gt2jeinhizt.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gt2zboxnpyc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gt2liolthlc.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2vhrtmbmd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2fucsgeyc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2wfuhsdwr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gt2xfgegsyp.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gt2tjfxegis.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfsflfhs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gt2pwnsqjsk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2ulfsknbr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gt2ygorutye.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gt2hqlctvzb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gt2etwgcuta.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gt2lqlvmlbb.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlknksz.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2wnlpgizo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2jbpgbxos.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2lygjfyjr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2wzbktdnq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gt2lbevxgnv.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gt2myhpbmaf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2qvmqblsd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gt2uqrmsbtp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gt2olcrxjkx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gt2wfqzxagt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2jcxduhsw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdmgpzns.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2gantzobu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2gwezcntw.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gt2lhwgqako.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptrlupqo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gt2rxsjxusc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2vjqfweyx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gt2sbwfmzcc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2uxxlmeta.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gt2zytmhgsi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gt2grjawikz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2rlnhqjuo.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gt2jgtjalhi.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2akhdjiwz.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gt2axonzhve.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gaiknfxv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gt2fpseeftt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gt2lijeihrg.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gt2uinrxcuv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yueranfly.top/Article/details/gt2amwvhcfr.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gt2svahuzpw.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gt2pzhljjor.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xojezump.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gt2toagorjg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gt2uxeihbbe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2wnsdxoef.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlhrtrhu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2oahbzpqy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2ddewoqlh.html


<!-- 参考信息 -->