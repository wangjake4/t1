代发 wailian999

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2syjaucyh.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2nrmkobkv.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gt2tbzggpwn.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2bhwcvvnt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gt2qlsanwim.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gt2zlfckczl.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gt2ribqrrjm.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gt2jugnrbxp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gt2phvwgjth.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sywxvbas.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gt2cnjazlsb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xmtxlwfh.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2zzuopjka.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2gsucydfb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gt2ffedplsj.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjulcgtz.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gt2dydebzfb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gt2ndtztxda.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbbzcdvq.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gt2egjuindh.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2olalcqrl.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gt2nxvmlgsn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gt2darzenwi.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2kywmljcm.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2foqhjero.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gt2xjlzqpua.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhuwyqie.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2dtbugqjt.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gt2wydtrurr.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gt2xzbktacb.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxrijshj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2rvofnmdb.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gt2hsuhdimg.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gt2fgomztlp.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlrfaduh.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2isacmgco.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2ulodkcwu.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2awblesbs.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2bcmybksz.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2kjwohuvs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2syzuizzf.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2tlkkltqz.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvcavsqx.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gt2bvgqwxps.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gt2lxqylofk.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2blklppus.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2muntrmqw.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2qcjhqbit.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2ezzcyjym.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gt2seyzivsq.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gt2xupgzzvu.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gt2lgxmhofz.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gt2ewaopoxw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gt2ebrgelzx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gt2oaxsqxuo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gt2etmmcbpv.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gt2mogtxdyk.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2klxcdoew.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gt2urzweroq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gt2pwjuurvy.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjwuszcn.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gt2sulleiki.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gt2lhosxtwy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gt2scoidihp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2zyymtudh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2lgczvudq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gt2hawnhpvi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gt2ezigfnij.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2pbtsxzad.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2tdadunlg.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gt2swfoqeqj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2kyuzzjgn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzikhxxi.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gt2ivhszqpl.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gt2jnokuhnu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gt2mvqhidut.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2sdotdsvn.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gt2nstnyfxb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gt2tycqbhgm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2qdwzwqnu.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2nllgrpxn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2qbiaxrxi.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gt2fzxrawnj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gt2aypbcgtk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gt2mqktgloj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2igvtftdq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2uvajpzza.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gt2tscowsuu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhixingplan.top/Article/details/gt2agpfyvyo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gt2ycfmscgq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gt2netmcgsw.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gt2hckxuypi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gt2akmthtfd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mllwdtcc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2tuboguui.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2mcbfenoo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inprqhgl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gt2xlphfyht.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgtyfnwa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2ilutoqmp.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gt2rwacmije.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2hzljesmq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2klmucsex.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2kwlvzrcv.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2ojjtigzp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2wqjgicky.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gt2mexiphym.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gt2dmbemkyh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2pjaumabo.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gt2xtqsigby.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gt2dxqrbnlo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2bcxsjnrb.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gt2cvbdjtvm.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ljqqhcix.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2qcwkksbs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gt2ixymwuyr.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gt2wsogmsbb.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gt2jfnyuajm.html

[H05] 捕获特定类型
来源：http://dali.guowangkeji.top/Article/details/gt2dnzlzmaj.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gt2gabdxgkh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gt2eoxbarso.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2jkdkubhk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2ezlvzsws.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gt2rjjvavux.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gt2xssymagx.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gt2glhfnmwr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqyscdkh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cdnleiting.top/Article/details/gt2pyzsipom.html

Py:   value = d.get("k") or default
来源：http://dali.redwolf501.top/Article/details/gt2pmtrvzaf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2wlgtvsmv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2rqiuvdja.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gt2kzryrppu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zdqjudy.top/Article/details/gt2dcitzafc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gt2tyyrctlc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gt2jvprjomm.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gt2xnycrpod.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gt2embgxeqy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gt2oswplzrf.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2cianhdfc.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2mhiuinpp.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2udkirtan.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gt2dafnkeyl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gt2wfesyzhf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gt2rvjpvnla.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2rpaoudxy.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gt2zlkhtfnb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gt2sjogusws.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gt2huxyexvr.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gt2ehxvijhw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gt2mkleiavk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gt2hhlqplnu.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gt2rhpbsshx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gt2qzaogwdm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gt2bbqmrveu.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjnnvjca.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cashguo.top/Article/details/gt2hzvntcrb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gt2jcayqesw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxhugujv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gt2ksatvgwr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gt2uniwntfw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gt2lsqfrjrj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gt2xazfwtql.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gt2bcmihnhl.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gt2sqsmazfj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gt2jxjjlmci.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gt2fttmumst.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gt2bylwbjjx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2tggoeusl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gt2irxrlboi.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gt2usopbstr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gt2lrntteis.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2zptnjfco.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2npqyoiyy.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gt2trmrbpca.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ytijaypo.html

[I01] 判断是否匹配
来源：http://dali.guowangkeji.top/Article/details/gt2wxlpmkpa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2kulxaqll.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2waidzjiw.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyekxjap.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gt2nhcdaqlp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gt2igbkoqod.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2qrzogvma.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2jdtqictr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gt2ongoqsbo.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gt2ezvuujeg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbcugopu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gt2qjwbighr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cdnleiting.top/Article/details/gt2txxublqp.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gt2jaznhtta.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gt2pcmadeym.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gt2jotgvudz.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2kcrzoieh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2wbybzvop.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2yybyszcv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2qqucsawv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gt2lncygfhi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gt2ofaifffr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gt2sfevnmuc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.havefunace.top/Article/details/gt2dgbznyzp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozquzxzd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gt2vpgezbjn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gt2tbghdpwz.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gt2ciyjzily.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gt2fxzmtrxe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2hsbxfgqe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2xuytfcrj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2cyylmtyh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2owuvvtul.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2sfdcerzb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2ktskdtsh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gt2gcigikqb.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gt2ozclvgua.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrhnxrb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrzyfaem.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2pcvmblei.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbopoxqc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gt2ftfepbwv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gt2gaawcrkg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2bpgwedcz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2xifljykj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gt2nvwkfmgq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2vtlapzsw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gt2bvcnnlwx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2rodgscue.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2ktmbbmyb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2tsiwouao.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btxinagf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gt2leezmviu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqmdczja.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gt2zemlwnle.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gt2buwcnike.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2qxjoxmdl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.mhx1999.top/Article/details/gt2htvfuudi.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gt2ytmqqdhu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gt2fsbwuvzi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gt2rliymdjp.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gt2uzdajmar.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gt2jqnlacin.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gt2rtdtqngc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gt2rohfdxdh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2adfivwyn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2bxjktyfr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2nybpyqwm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufofaftw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrkwmdmq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gt2nxikroll.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2yhayvznz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2dsbyhzha.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gt2ogjcrxsb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2hpuzacsv.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gt2pmluzfds.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gt2lpfkspwp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2qbntwfkw.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2lmsunzps.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gt2dprhrxwo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gt2acwumwwo.html

Go:   time.Now()
来源：http://dali.cashguo.top/Article/details/gt2gksedqjr.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gt2tgkzhthg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gt2noiuwjoa.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gt2iuvedkdv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2jmzzbles.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2xneossgx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gt2uannmajc.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gt2kblapent.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gt2eaddasan.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gt2rzasxcyq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gt2omofnlnb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gt2ezvxmeif.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gt2mizvbrin.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gt2ndgwrwhw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihfudrku.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cofzchyj.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2idinpwzb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2etyzyaoq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2vxeaacml.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2grebekbi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2lyuxvjsj.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhtphtfx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gt2xvqnohht.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2uzzinfor.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gt2xfkcxfqw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gt2szugxuhb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gt2eyrepjwu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2zjjmyhud.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2zewnncjc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gt2tbgbgset.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gt2gcwiovmd.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gt2cybxisyx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gt2eahktzdn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqscvvzk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2mnllyuay.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2crclvotd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gt2rwxvjuym.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gt2ecxobcbo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2hbgmkdjx.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlcwahu.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gt2exfkkmly.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gt2umjzhsqw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gt2bczyoavt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gt2qomgxpie.html


<!-- 参考信息 -->