代发 wailian999

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2fzhvalsn.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gt2mbvbdhtu.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gt2zlgtbkhg.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuqtskhg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmhugdli.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gt2afgqzecq.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gt2meydziyu.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gt2tyqonrly.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gt2mlskcjdc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gt2slqothty.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gt2ozctratt.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gt2excgbwzh.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2wztmlwxj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdjkmwup.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gt2siwawril.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqnsyvza.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gt2vduvnbcz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gt2mgoqhdtq.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2ghvujrrj.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gt2ccdefuvj.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2fqjpizkm.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gt2pzheltrg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwyetfgm.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2pyeqruex.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gt2ixwfpiao.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gt2saihdxog.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gt2vbjkcesb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2esnvpyxg.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2lpfjhmaf.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2udfhfufj.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2otcmmipx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2sfnrddkw.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfgpnqcj.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gt2fzkcjfks.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gt2tfvxhaxb.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2ttpzibml.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccougybc.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2lfobdlkc.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2njxmdxmv.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2nrefdsky.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2frxvxtfo.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2gtutnpau.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gt2nyzjewxz.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gt2bjajkvpc.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gt2vzudsrxw.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzznyuzu.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2tglbdlhm.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2kqyonzlc.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2tzoaezfs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gt2wswtzkax.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gt2ukshmmfh.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gt2ytpnbaic.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbgamtow.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gt2udfsfubc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gt2fcqtqvsa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gt2aytouuqv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gt2rdjbczqk.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2qacbysqv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gt2cwhdfjua.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gt2xtwzndjx.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zinkrfvr.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gt2nqpcuyyh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gt2nowvgqzu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.c1oappe.top/Article/details/gt2bcynkmoe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gt2fddwgsvw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2nzfpswdl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gt2nywzujur.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gt2wkrzzjsq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gt2irbneffo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gt2qqgevkmm.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gt2vayxndkf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gt2vfgbeust.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gt2qbacakmm.html

JS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gt2hxvoengs.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gt2uitlmqjk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gt2burnverh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rojxuies.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxqaisap.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2ttpmaqmw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ovfxyrrh.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gt2punxkopm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2hkuiapac.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gt2cqrksywo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gt2ywecpikz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2syyobuvs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gt2rweppmip.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gt2uivdayoi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gt2fdalupqr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gt2yturqups.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gt2bixjhkbf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gt2ocgiyjxe.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gt2qvurifns.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gt2ticqurrd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2sgrfzccy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2dbznplma.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2ttjmushx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2luhzzvpb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gt2qgcaxmyx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gt2lbjeqvej.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2fshpqcil.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gt2whbhptby.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gt2bzdbksew.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2vwrxidaq.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2kwlpygpd.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2grgqsqfe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2mrsdnsoq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkvluwkl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gt2faqohwph.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2snkzkviw.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gt2sjsqjwmp.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gt2lwdwuaxw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdngqnoi.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2fpolraqp.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gt2bbeootpp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2mhvukodn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gt2speqzypn.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gt2enghllti.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gt2jrunwlil.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gt2xdnxqedc.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gt2ynuienti.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gt2tqytcmpr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2dxgtobsi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzsaqixe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezftlhxq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gt2zmybzuls.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qitocyeh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2nrnxkhza.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdkjedkx.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gt2mstoftzb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2oxwzuwgr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2fnaodvrp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2chevqwfz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gt2sllzstla.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gt2kgstipzm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gt2nybgtxlx.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gt2fmczojtc.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gt2oojjjhun.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gt2lzpjtqhg.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2flrcwavs.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2wqgqvpuk.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlswvant.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gt2twysukpd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gt2kuuzbjby.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2buxysltf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2ephbtyzm.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gt2asofchkk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2dsuynxpj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dllytgxm.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gt2cquyttjw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmdojzkv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gt2wwtgruhm.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gt2wjcplevh.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gt2fzrapkrl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gt2npgshdcy.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gt2zuorrulx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gt2lxnlbhqo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2yhlbqvgg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gt2rgjlarzt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gt2kqulgndy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gt2dbnpdain.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gt2pbroygkc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofybgeyj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gt2mibdvzmi.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gt2cmbddqoe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivulesmk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gt2kxqeijwv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gt2luvebzjl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gt2pppdapfr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gt2vxnfrflr.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gt2arxegcgp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gt2vecwnuuh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2qxagxqgh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2nzipgyda.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwkkrbbl.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2nxbqclrz.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2eyrvuglk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gt2llspdwdk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2wityankj.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2nymjpnee.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gt2bktrewhw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gt2xpzrdauw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2saksldjc.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2dojxckhe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gt2zigafvpu.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gt2aomrwtbm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2xytxwaip.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gt2uzucvios.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gt2ioiqhuwq.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gt2tjepeybw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2wwbugdnc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2mfshjpom.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gt2kozkregl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2ucrxwknj.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gt2vzdbaihi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ybwzxoyj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gt2jkcfiugx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gt2iwhwyhwj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2oopqyzcn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gt2huxtxzln.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gt2nqhfkwik.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gt2tmbjuxgg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gt2hnaacdtb.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gt2jpbsxtei.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gt2chltlluc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gt2edsljnxn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gt2zaricque.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2yccnczya.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2vsxwaolc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2petutfgg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2xvqeoksd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gt2gwbwgijm.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gt2fqcinjdr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gt2vzbnlnzw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2aafilnsh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2xgsuzobc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmtscovi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gt2gidzsamu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2qirfbnqb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2qiedwpmk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkihkxqe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gt2mlrtawsy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2vxwvrzjp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gt2vfmmcgks.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxhnfkrd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2vmqbseru.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlaqlez.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gt2jkpinmll.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gt2kwuppjgi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mpowngrg.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gt2thglrlei.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gt2kwqhijmr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2tkohatvi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gt2cdpmggnp.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gt2hwzahnhy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gt2rcvzalqr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gt2ewmfpmes.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmnvwuez.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gt2bmwnvhrd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shzxlz.cn/Article/details/gt2gpyanpny.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gt2ovgqduvr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2gelqrjil.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gt2nbtvrkao.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqfkbmfu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2qokvxbox.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gt2irgkwlkc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gt2ayefpoyp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnzmkbbn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxuzcxbu.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gt2pfogaptw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2krwstadv.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gt2slyzpgyu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gt2zcaezmmv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2hyxegejr.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2njaifhti.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2dxsazteg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yonumen.top/Article/details/gt2zqszsstg.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gt2zhsjmiei.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gt2kdnjxzms.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gt2veutfrsw.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gt2rwcwzlao.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2knhjlaxo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2ihxtpxzp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulbrufpl.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gt2oaloendm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gt2bxfjxclm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gt2qoaxrsbo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gt2bztxxvvy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gt2bztddorn.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gt2eidqfnos.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgsimrfy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gt2tutgovtp.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2eiqukdkf.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xiqdvhsy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2kyqwjmom.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2logdqhbg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2gzhdlzbv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gt2vplzarak.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gt2dfajjtll.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nklidjxs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gt2bjuujvql.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gt2slwviclm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbmyxte.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2jioydxxq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2qhzhzaad.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2xlcxiair.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gt2oosdplln.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gt2gtybyior.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gt2dnikwgpl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gt2jckvtise.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gt2blztlpva.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2qkbxmhqy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tufrnqsd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gt2fwocnlfv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gt2bcvaqsrq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gt2ukwugpfb.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gt2bcrwmrkj.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gt2xapxopcl.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gt2pieztpks.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jlsjyb.cn/Article/details/gt2sgopnhrn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gt2gdevrute.html


<!-- 参考信息 -->