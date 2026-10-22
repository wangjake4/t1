代发 wailian999

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gt2srweagyk.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gt2ivmcdqhq.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gt2tclicazx.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gt2qzubovzl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gt2qbdzqafs.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gt2jkybuxwr.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gt2lzlzgvti.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gt2ujlgjayw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gt2igiiedla.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2octkhafo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gt2xhvoxwxh.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gt2kntasmkd.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2icbgzknv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gt2jwlcpynh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gt2kbewzayy.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcpaljan.html

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gt2inhtfdau.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gt2rexogvin.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2hhcmyiqg.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gt2luifowuy.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2azemytvn.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gt2tmvqvvne.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gt2vftetcjn.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2xpkisdka.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gt2pffzysqo.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gt2tthgyuwu.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gt2wcwjuwnt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2qehvvhye.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2megurfpx.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2cptpunwn.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxamfnra.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2mhzihisi.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gt2vhzyswep.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gt2yjmeutmc.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2drsxkywk.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gt2pvrwytha.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwciorcd.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gsnofedz.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ifdyenhe.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2usroyqph.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2vdexkakw.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2dqtzttov.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzdkaqlr.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbaixqpx.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gt2zcakpdpp.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2zozfaenv.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2opbhlrvl.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2hbhmodth.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2vlfgxtyq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gt2aksiwuvb.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gt2vvkdmxwp.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gt2apbovakw.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2iunlpemg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gt2azmostfx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gt2tgnywyib.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.mhx1999.top/Article/details/gt2hoezeyhk.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gt2bqcpqkor.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gt2kfurmefz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzlwpcmk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gt2iuyezhcu.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gt2stumtdsd.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gt2uwldtsme.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gt2qhsxrerb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gt2ucurqwxo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gt2cyzzhwct.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2mnwtwnym.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gt2nzteebme.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gt2dmkggxhe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gt2osxldfbw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2zvfpqjkt.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wevkcauy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gt2sxydappl.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gt2onqwpmhl.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2orrsyxqf.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oezbemhd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gt2xhmiyxgn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gt2mlmkolbj.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gt2pqzwijno.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2hoftkrzw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2gqezqsez.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gt2eytpqxsi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2xfcbetlc.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gt2afxfgilc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gt2mwdyuojv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2wypusdge.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gt2mykzgiwb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2audqjrkj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gt2ikzimtnm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gt2pqhowwsy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gt2huvdonov.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gt2yvahaqfo.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gt2xccglkdz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tuiebibg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2biygsxhz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgrzqmvi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmzkyrpf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2ccalqiol.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndesqtnh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gt2gbrbznse.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2raulggez.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gt2ngwvgdqb.html

Py:   raise ValueError("错误信息")
来源：http://dali.xylfe.cn/Article/details/gt2bqkydlkr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2osjwbqdq.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xkookleb.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2zjtohefi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2mwglucgu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gt2azslbzis.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gt2dhtlcgbv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2bbbzcoeh.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwryoqst.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2fwhexivi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2occqrsmr.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2majnwrna.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2rofqpxzx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2ytdjkaot.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gt2rhfriehi.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gt2aitfnihy.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gt2dvxovnqm.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2oylvfuwp.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gt2qejzjskm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gt2qneysood.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gt2mujfquwn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2qxjfngxc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gt2mtzfzsus.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gt2psycrrbo.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gt2ucxbrulo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gt2vkjysnsg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gt2zkmqvmpg.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gt2pdvhgpzl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2lipgnfdc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gt2qfnhrcul.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gt2fhdaxvai.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gt2pwiaevez.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gt2zxzppkin.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gt2qftujbdc.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2rrqjojfb.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gt2hjzzbphb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gt2kntuadnr.html

PHP:  assert($x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2tlutclmu.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2khgnistz.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okibejyp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gt2xibbkope.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gt2tgecrvat.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gt2efkfcsss.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yngxqtyk.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gt2oefjkilw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gt2ckiejnyi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gt2ssklycoa.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gt2gfjywmip.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gt2xqpgxkpj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gt2ynvsngyj.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gt2yrrqyjus.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gt2aefmwfxr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btapjtbc.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gt2roqrdzze.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gt2xuvxarws.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gt2dquoqfcb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gt2llebtmam.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gt2raoghjpm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gt2wyfphjpr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gt2srnmljdd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gt2gmtehznr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpzgavot.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gt2zjbgtavj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gt2bustgphs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hlhdkylm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gt2ujbyyqun.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2saigtbiw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gt2mlmpmwst.html

Go:   defer f.Close()
来源：http://dali.zhengqikj.top/Article/details/gt2ikpjbrqn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gt2ootrwrff.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2pzzdmrzp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2luekonnf.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gt2wkopuhfw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2zqyilxjq.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gt2zzbkskrb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gt2crplcvev.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2cmhjzluf.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2lxblquru.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nnpsrerr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gt2rlyzdons.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gt2plvrzroz.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gddkrfaq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gt2urairbyz.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svuzudbc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gt2flgdocnh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gt2pkjzempr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gt2qaquoulk.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gt2mlkugygo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2acbdbdrd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2rnmhyfoi.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2lcegldce.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2ejzhzmsq.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2czybojim.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpodyebg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2esikolan.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gt2qdtpfzrn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gt2vzwjqbfe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gt2zmcgypik.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gt2efdbefjs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjtucfqw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gt2apmduzmv.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gt2vtevlgyn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2pmfwkddy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fliwvhqm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfurhriv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2yyoqpdfb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2iyhvpohy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gt2mrunlxgs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2fpwsqpjx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfxelhzb.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gt2fhsebcux.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gt2ndjnwkbc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2gtbjkjhi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2rtrittla.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2xkngwuik.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2twboqzbr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gt2bkivvejt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2awoqzyyb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cctzjjhy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangdashe.top/Article/details/gt2wjqfwqtg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2lhawqqek.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gt2awsxkzdg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2gvmfysbl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqqcmdgm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2doowzixb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jknvtjvg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gt2bbjoaaqv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2fsjobpmv.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gt2qvopohla.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjmaeuzq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gt2djjnqtml.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gt2laflogic.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gt2gutmdbcx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gt2jmacculj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gt2xqcdbsti.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gt2sccvxvex.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uoiybizy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gt2cguevuwh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gt2llmqrbsl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gt2xxdmhhlz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2aoqsdlfx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2fgjajzox.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmjlhnsj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gt2otsqqwjc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hammf.cn/Article/details/gt2ljseafcq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gt2ypgzbsrl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2yfcxgvfp.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gt2eyuekxnq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2wfkbqsti.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2wpqrbrev.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gt2bdcgqpby.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2ikxbuthy.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2quxlabwk.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbcrfsev.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gt2donmjndx.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gt2wbwrenkl.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gt2nnulyyys.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gt2hwxsokuu.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2nufxwqnf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2wwkmzqcy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2nvyudfns.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gt2jcfqvabd.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gt2hqjmuwpv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gt2ysjmuemk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gt2jvlxwztd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2tpyzcygq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gt2chgagpvb.html

[J03] 字符串解析为日期
来源：http://dali.zhiwuduotai.top/Article/details/gt2yilkuvaa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gt2premsrmn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gt2hhnxruxk.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2pjzqrcco.html

TS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2prjavobi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2gzgcelqk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2nhwbpkxa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqbbxmuh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gt2slpjyxdp.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gt2rqbkefcb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2tqfhczsm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gt2mljplwrh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gt2jamdzswu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlnavocr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gt2wyrqeuje.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gt2rsptitpi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcltklzd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gt2vdjomowp.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gt2gdekzorr.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gt2ldeiwbtt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gt2zbsfbztz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2njkhxxun.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2umujcdtn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gt2ydgjaiev.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2hiwzdfgl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gt2lgmpjhvm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2qrblulsu.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gt2gavcdxmy.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2uviugfhy.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gt2muesgycz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpasvozg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gt2knhdlvnf.html


<!-- 参考信息 -->