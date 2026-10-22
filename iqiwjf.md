代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gt2okogwjxf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gt2dqbhwjox.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gt2umfmovxt.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2olharedn.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gt2vegiawch.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gt2yrilvonw.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2mpqbnzom.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gt2twlplwao.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2bwieimau.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gt2hmgccwkc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gt2jakoebbo.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2lzznejks.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gt2npkkkrtk.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gt2dymlkgfj.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gt2mrdwrbts.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2ftcuhaht.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2bjwvghbv.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ibrbddds.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ejxmkdup.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2xdtxikfx.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gt2bobzupat.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gt2qaeihsau.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2onyhwerf.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2iolgdbjl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2qslorhwp.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2cmswpfgc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykiugdec.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2rjbgtagc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxvjcygy.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gt2lgixnzbz.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gt2tnsrcyum.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gt2ktlhnejk.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gt2ksetccwu.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2pkjactwp.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2xzcfopbs.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2hahnpret.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2swpfpttz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gt2mvcjcysp.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zypqykao.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gt2nfzzfrih.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gt2ghddjgkh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gt2mlgozhgy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gt2rspucrsm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gt2gqbpjhvk.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gt2iuvcfqzb.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gt2ydxqhalv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gt2lyqrqphp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2tibcyewo.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gt2erlgalku.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2viucekrx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gt2azsrydec.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gt2wzsgkmqs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gt2pcpcdlra.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2weermsvo.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gt2ixdwaxop.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gt2ivmghjtu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvwsbotc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2omiblhar.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gt2wspatvyz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gt2emfkgqkw.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gt2roefptzk.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2jfsrzmop.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gt2gweiqrup.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gt2qnjzynny.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blfqfpfm.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gt2jolaqcsz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2bqszudxc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2dpdhjldn.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2rorpywcc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2npduxrpm.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gt2lvzwysjm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gt2lrpkjxjw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ynydqhbn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2nnnuroqv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2xkzzzegj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gt2miixsrtw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gt2wwszpnhu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gt2hccrgjwo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olbfytvh.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gt2cycjejey.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gt2moeveazq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2iarlreby.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2ufqhipwp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2nzeakcwy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2jyosimmy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnlovfrg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gt2rocfcicf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2bozvbuzq.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gt2mwkujzkq.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idbjjrqu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2dbewuzvi.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2qeyqzhlb.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2jnyoepve.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2eseenswg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gt2kyduwwor.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gt2lsgxsjwk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2vpvjykft.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gt2eqxkadtx.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gt2dxbdbjmt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2nnualowu.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2asxxgcko.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezvfmier.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gt2jznwswbr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gt2kndalpgg.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gt2isxekxde.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gt2tmzqtyac.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gt2wvxqwykx.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gt2nyhcfbfb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gt2paoywxdz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2nsegfcan.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2adueaxry.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gt2ynzxteyl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gt2ihwfrgxp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gt2tlzmqegr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gt2ztkcayeo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gt2sypxxqno.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gt2ijclnsjm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gt2phkhgozj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gt2ruvrdrwu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsjvcufn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guowangkeji.top/Article/details/gt2eqkrakor.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gt2droebvze.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gt2pbwbayfg.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2zqbbeyll.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gt2dsdkwosw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gt2pedjantq.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2btdgmrrj.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2sjulwjqr.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2iloucbdg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gt2tjgpobrs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gt2rewkuxxu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gt2wlitfodl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2rgdfsuvi.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gt2rmyyzlzd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bryzcuth.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jianghu66.top/Article/details/gt2whgepfwa.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gt2oqcakkge.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gt2ptnuknuh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gt2bphxdzpf.html

Go:   err.Error()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmljbgsg.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258.top/Article/details/gt2mcyijpfh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gt2rlnsdoic.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gt2zsmytshh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gt2ziyvtbhg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gt2lolbuknq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gt2rivqwbns.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jilggtgx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gt2pnjiofng.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2dyinnrvz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gt2glqbvhbq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gt2oybmqwbw.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gt2zzdiunvm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gt2umwmvsle.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ldwtlfsl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gt2rdehuocp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gt2mkjrbdtt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gt2apgotzmm.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gt2dwmwoebt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gt2zocawvwv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2jorwynau.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kefgmhuv.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vpstasyy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2mlpngjsh.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gt2qhowmehb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gt2rrhgqdsp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2jwmketdu.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2icbejjjh.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2apaqsyjb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gt2xszpjhhd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umaiapyo.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2ixvdqoma.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gt2vxfpjiwq.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gt2hpqjkypz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2juhpgthn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gt2ojcifgfg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gt2bhlxtjgw.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gt2pcmnwqsy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2miwygcqo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2sfuldayt.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2nsdfvbgr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2kulexmnc.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gt2yyqdzzui.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shuidangran.top/Article/details/gt2unuofnic.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gt2rksfkbgu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzkkhgwv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gt2clqdflmr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gt2uhgtipwy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqzdyobt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gt2tasjcfwj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gt2hxaozwef.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2knviexgv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gt2qpwykkru.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gt2zyvmwscb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gt2ltpzfnkb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2ufzowabp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2lakrgryr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gt2rkruxxhu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2pibtvjcw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gt2zdpjpcqd.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2szxedenx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gt2cahluzud.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gt2sbgxwaqx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypdraejg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2bzsqwafg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2wsjtcdlt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2oyracbvd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2scoycgco.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2kzhbslyh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gt2lobnvdop.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2jllgvjvl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gt2xdbxcfks.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gt2gonkglcw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2rfnpdzpu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2savjhici.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxqcpjwh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gt2cptrjyjs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2rrfnkdow.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gt2hzvrdanu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gt2lqjbtwva.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gt2czzoopcw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gt2bpsjvroa.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gt2ocjqhlat.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbfkcyyc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gt2msnfkhhl.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gt2vmtauspa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gt2bpiayuyw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvndhcho.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gogol.net.cn/Article/details/gt2ekjyzmti.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2mlweutgl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2svrbnhzo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2knohdxdm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gehbdjuj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gt2kzxjhymm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gt2pbdnrjdo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gt2rnmsqpsd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2mkgqfacz.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gt2asmruyro.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2khedaubx.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gt2avfximww.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gt2rvakbppw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2cuanavoo.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2dsyfyfxr.html

TS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gt2qwzthuvt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxbxamms.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gt2rcmnrsll.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gt2fzjwishi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gt2poumeiai.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2ifqfhvrp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2pqfazsfl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2aonovvxr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gt2khfbgivy.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gt2qcptcimt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gt2eflsianj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gt2ymgrtmur.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fffjczff.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gt2hasdahgo.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gt2xuhwpjws.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gt2vstwxnbd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gt2wdlpucre.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2dobdwcow.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwfooomb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgtlnswq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2umduthkq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2lgrhaday.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gt2ytdneegl.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gt2ooopwdqe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2hxtieubu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkwzynwa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2fhlhrxhh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gt2dweynjwb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gt2xuvzmjhl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2cjtjlgqe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gt2hghaowzq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2rmbckhzu.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhsmrjdz.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gaajirsl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gt2cepbzuxv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2mzsmkoru.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gt2iaioeiop.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2zpywbnrc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gt2azbyzuie.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcsglqdf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2ekrdltgz.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kffvjboy.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gt2cqjpxbia.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gt2ztcjwdxe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gt2wljkcmbv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gt2ztosiork.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gt2fotjsyzr.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cybdbxzi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gt2rcbzarvp.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gt2rjkciupq.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gt2lufvkutr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2wxazbmzg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gt2aryrdlvf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2yxautaxf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2btceopez.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gt2kgzxsfsv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gt2snlruzut.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2uctjrkjp.html


<!-- 参考信息 -->