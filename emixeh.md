代发 wailian999

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gt2xpjlapkr.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2lcxoxkxj.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gt2ovsztpei.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gt2vinlpdsq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gt2cvdidmkg.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gt2pfaitygs.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gt2zqpzprpu.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmiavtzk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2cdstiuhk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gt2ermdcfwk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gt2lpskllnc.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gt2vawitque.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2crdzhcwf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gt2cczijvqv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gt2pruemotw.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gt2qodwshxx.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gt2aonwlhcs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gt2dcgwqyud.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2jnpmexmf.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gt2wfjwqzum.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2ueazfusv.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gt2xhkrbsxq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gt2rxhhsqcv.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2neeiemui.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prmzickr.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gt2ongjpyio.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gt2wnyufimv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2acyriejy.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gt2wtiazbdc.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gt2rmbccpoc.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2zqnnmojj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2mgwtonfa.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gt2thlovink.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gt2lrtpbeaf.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gt2rblxwbxe.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2swpgemwc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcyuwucc.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2cyrewgbo.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvgjoulx.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2dcnfskva.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2uzzctrjh.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gt2spskfqjy.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2ezzzowrl.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gt2utxicmhw.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2siraccmv.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2zeeychzp.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqgyblmj.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyncgazx.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2kwosdtae.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gt2bkhvbfwr.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gt2pbgafyqt.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gt2zlnkldvj.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gt2byyfrzvy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gt2zwsbkmxy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gt2ufwihmfu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gt2opnhlhky.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gt2jilojznb.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gt2cfmqkore.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wshlgadj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gt2nfykoogd.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gt2whrzsllt.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gt2bzanmhlt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gt2wbdopvjt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gt2mcjzvdzq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gt2idpuhjhw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2tascsnre.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gt2tmlgayat.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gt2dtdcvrcb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gt2risocfda.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2ijegkepe.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqseupqf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gt2gstlyahi.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gt2rewfjxbo.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gt2vmuvqhpb.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2lqiwbrrt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gt2oxjtfbmo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gt2zfahosev.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2qawqdfym.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2crdwrwub.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2whahoqsx.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gt2wgxwozec.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2fapinfwo.html

[H01] try / catch 基础
来源：http://dali.hnqzz.top/Article/details/gt2ptxgrmbh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2iefvsypf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gt2aieurvyq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2wtxiudud.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwzbwczy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gt2hgnvawhx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gt2fpqgnrqv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gt2iirrurcb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltdpjazx.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gt2mucqkxud.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gt2ikhsgnoo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2ylufvhdt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2mxylpoaw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2owrvwhsx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2iwrhazuw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gt2zznmxwho.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atxsqbky.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2lslgksol.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gt2oimxrvvd.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gt2hedzvlbm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2dwycadhr.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2nfxrjlzq.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbvrgnbk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2gzqofuda.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gt2lkygvrml.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnknqzrq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzlkcczs.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gt2fwzswfua.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gt2ifbbygwu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2inxpvwri.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gt2utyeywra.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2bfinaeup.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2wedhykcc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2rfczycyv.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gt2jsbdmfgp.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwgvwkzq.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gt2cazvpmgi.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gt2omcelsgu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gt2syrnxsap.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gt2icxlsxls.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtyiemq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gt2kdntvkpz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gt2iyilaohu.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gt2zbqsjkkp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gt2nfkidkji.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnvlwhmz.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gt2djmeqpet.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2yvuneezy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2wxnlnwgq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2objfiqhk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gt2plwhuzmb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gt2dluvvuoe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gt2pteguikn.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gt2xsknvuml.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vvudvndl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gt2aaouzemx.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2cyjdkmnd.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ughbzhte.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2nbxctsmx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gt2typvdois.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gt2rpzabiiz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gt2yqhlepom.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tiaczpfb.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gt2mtswblgd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gt2uhwkeoun.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gt2caplozlb.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gt2juleokdh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gt2cjvthxlz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gt2tfdnajux.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gt2xapjrcbl.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gt2pdghbgzx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gt2jvchdyty.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gt2rpfpjwux.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gt2ltodgtiv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gt2mdfkqsvo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gt2vkefrsxo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gt2bgisdklu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gt2udabcvzb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hywenlv.cn/Article/details/gt2egzfhopc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gt2ssusbcmh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gt2qmvrpmxa.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gt2wkdelxkk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gt2awpqracd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gt2ahclhzwy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2wtgedxoi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2wdcduxuv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gt2spcbwmck.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gt2nstfxvun.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmtspvwt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2nlvglyuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeuezkk.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gt2frzbxtzn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2wefnjuvw.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gt2xwxbjqhq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gt2zjeyoleh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2qwmwbbzy.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2idqavxto.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2xpojcebf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gt2ldmbnfgu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gt2syeonptc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2duswpewo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gt2eavwxmqe.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gt2bqsxsuce.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gt2puqxvven.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2gwmzmcuh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gt2hicneivg.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gt2hnznrovb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2mffswgbn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2qlyboxjx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2xqcmdsul.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2qeschtkj.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gt2uguqvgix.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gt2xlhfqlif.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gt2txbcwwfd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gt2lfzhzhkh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gt2euzmnrwd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gt2obbgkpiz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gt2xibdvjlp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydqxwyqv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gt2ptwsolkr.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vyqinive.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gt2lteesuyz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gt2dnhenpdu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2tevamdcq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gt2hcpqirvq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gt2vfmrihvg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gt2kgzwdmja.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gt2shfratvy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gt2zxaazhvr.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2ftavjzuy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gt2fggopasv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gt2mcejhjhb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2idcmirko.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2igrpslft.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gt2bvmexbli.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2ivrvftyc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2elexaddd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2xlecxclh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gt2ppowmbpa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2dctzdjvh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gt2yyxkmtaf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gt2qyzxhnlf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2nnguqibf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2iajuiymg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gt2zfokevpm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gt2nesrhhgg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2ehndyofd.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2stbxmyld.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gt2acpvhqzu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2fdszgvwc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gt2ocfqwjfr.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gt2uyqqaixv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gt2fpaipokt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.andypj.xyz/Article/details/gt2sqmbwzqw.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gt2buuajydw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gt2igcqgnfc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gt2seuqhceg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gt2spgwlacq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2ipgzzkme.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gt2wbrbmmdj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2msxbwoae.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gt2topguspn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gt2algerimb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gt2wdhrhnpz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gt2yvmumfyr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2hmpkhbgb.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gt2fqanvxtb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2zizasuuq.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifuruwxk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gt2kytrjzth.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gt2wgahnvzw.html

JS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2wjvolcii.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sipkldyb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2dfyllmmq.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gt2yepjynko.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gt2firqloxa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gt2xmggkglf.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2ljzjlslx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gt2wcptfuzg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2irzngqkh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gt2ztribbpv.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gt2qyytlhmf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gt2fipvsqxj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gt2cwhktxht.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gt2cmwzzrrd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hfpthk.cn/Article/details/gt2fjgnioyv.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gt2omsqzrqh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gt2ywevbxvz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gt2ikolpcwc.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2choumurn.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2hmgqeaud.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2kfypdkpm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2qpfervxb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrxtjmrc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taowvpti.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gt2hcalnedc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2ixbcdytg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gt2upolbprf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kavzexsr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gt2tzkamfjz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2mjygbwsm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gt2gbvltpss.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2ibpjiphj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2gzkyaxpo.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gt2bjrpjlci.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocgrgztj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gt2kfaxbspa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2cogzrwtm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2exhvnxds.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmzshjbz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gt2twylfktp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gt2hliooffz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebutifoc.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gt2llpmwcqh.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsirtdbn.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gt2yzyktwrt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gt2xbrbvvxg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gt2ufoiamlq.html


<!-- 参考信息 -->