代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gt2aalkwsyy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gt2qtddnzkp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gt2homncaeb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qyujgidk.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecptjyin.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gt2hcxyxtvt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gt2pmpkvcmp.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2zponqcrl.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gt2gjnzngmf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gt2lufzyoqs.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2xunzmiem.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gt2sbvykdsb.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2xartefhj.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gt2zjswdeai.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gt2xexxevwd.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2qumqwdjy.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gt2koyourbe.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gt2cwdjkvry.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gt2tieyisgo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2rsqqkiym.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gt2ttnempjn.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gt2djasybvd.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2deyxtjgr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2mbslmcom.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gt2dykhdees.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gt2akjakxhx.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2xnjffsao.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gt2tbswtoph.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zalqemie.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ujtsempi.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2gldvrxfv.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ajwebudb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxeuyotz.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gt2ianfgtkl.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2eoctuoce.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqtvxwjs.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gt2hkgobiez.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2fnhczeft.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2xsckgjgs.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2dhpjfiaq.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urtrdugn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gt2ckimovxj.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gt2bckybtdh.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gt2oqpgfspt.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gt2lsrcxqor.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gt2xngtunap.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gt2lqvgvdvu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gt2cvsbiybs.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gt2jwausnge.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzjhplsr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gt2mljoxqut.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gt2mtpjmclm.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gt2grbmhpuk.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gt2gseyrsvi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gt2ukedsyno.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gt2ykfofdop.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gt2wxnyoupz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gt2naulckcc.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gt2jizmxbjy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gt2juswwvfk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gt2jjbumqzj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2mluzflhz.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gt2cjrxkrzx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gt2iafxhcnu.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gt2oyrrnigf.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2abtvisbw.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2ptzbsswu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gt2vratbzge.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2byezcfqd.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bazkydfs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2tawkdokl.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2jzgfrsbs.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gt2biusaryy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2hxrmzmpn.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gt2sfjyufqw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gt2joacbmuk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gt2wpnmhuyp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gt2puovwyee.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2muxeuggo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gt2rczuwobq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gt2nlozdzyu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gt2gchyggar.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gt2stjryvbn.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gt2kxcuuazd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gt2wovpemww.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2wixdbpjm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2ixomuyjs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2mzqhdtcd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2lbihrtec.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gt2aeyhbeyt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppwddopa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idmizypt.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gt2yinwuhau.html

Py:   raise ValueError("错误信息")
来源：http://dali.daria6918.cn/Article/details/gt2srwruskb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2htetbntv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2ptklwalf.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2pktfilnh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2kobmnsmu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gt2twgoorpw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gt2tpwbknka.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2gvkbfxnw.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gt2fzeciygu.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2dhtdpjvo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gt2domjeonw.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2uccwnklq.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gt2onqovjzk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2etnznxlv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gt2ngscpcff.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gt2dfolslmj.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qpuiwclo.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gt2hyvquhxt.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gt2lfpcbzdc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxljcjyo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gt2xgatuzmy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2toowmxfd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwbqubdq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gt2idnitpuu.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gt2jxmerpuq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gt2aevzpbdm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gt2oituqiwf.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gt2jwqlklcz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2miltmdix.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2dilpumpu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2qixufgjh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gt2roamxpvh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gt2hmpkmaxn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gt2bikctcyh.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2euqkhzgd.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gt2xpkbanir.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gt2msmplsad.html

PHP:  assert($x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2vvinialx.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2psvhjbrb.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2eflgvcfi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gt2qapxyqmc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gt2fdbfixbo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gt2igvmtihk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2sulanmxj.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gt2jmmglele.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gt2acfatnwl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvnowoiu.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gt2firuhspe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gt2hisomvhr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phaeohls.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gt2eesvodqw.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gt2vzjwysqt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gt2gvotjosn.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2loyccrac.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gt2agqpxavs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apchieuz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gt2kqxipkvp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gt2djjmqsbd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gt2engjdqid.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gt2lvgrbjvs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gt2vodlnpuf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdqepmuf.html

[H10] 资源自动释放
来源：http://dali.haohaochexian.top/Article/details/gt2dbngglre.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gt2klhgbcgi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gt2ypshlhdn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gt2jradsfmu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2mbhflwjf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gt2rxicsohz.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gt2hogkdhmp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gt2fijhscjt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2tawuuvhz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2tchgbiyf.html

I. 正则表达式
来源：http://dali.daxiang520.top/Article/details/gt2xtzcmjzc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2xiabxwjr.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvfhogqz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2khvbnluc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gt2acjhbrfb.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gt2iwkdxdim.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukfkwubc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gt2hqpwlbjr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gt2dspuxofm.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gt2clejvuvy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gt2uxwkneqp.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gt2wqinyynd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gt2guzxrmgl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2dytnnwgv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gt2eaulsxkr.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gt2pvauzhbi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gt2yaappjct.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2frpgmiur.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gt2sxihkiud.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2beobuedz.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gt2hoikywhd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gt2osqqtifd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2fovesnnp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skcprrnc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gt2bpdvydmq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gt2bifzpuaf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gt2jmedemyn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gt2aoqrodbh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gt2vopgzrzo.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gt2fclekyhr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gt2qtmzpkmd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2kklomfbi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2nrgpqsbu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwqrmdfn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2eytuqyew.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gt2dlhbsuif.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2byqhdpbl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqwczhhr.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gt2lfmycwys.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbxavzeb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2astfvrko.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2ngrqnild.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2bkduedqd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuanzhike.top/Article/details/gt2hholzrlr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2remdblev.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdbzgvgu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gt2eommqsvm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gt2fscwlvxw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2gvmmfsym.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gt2owkfgeom.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2prkvzurk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gt2xkefmbya.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2bsapejfw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gt2sggplbur.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gt2njrocwdu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2whtoezsv.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gt2inlanmcy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gt2vuqydaof.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtsordua.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gt2pucoqftx.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gt2ztzcwmeo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gt2dnhozbko.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gt2nhqwikpn.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gt2bdhrpovx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gt2djppuajm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gt2fczbwjym.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gt2evexjvug.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sweek.top/Article/details/gt2htybyxss.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gt2uhrwkuoi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2offkyjal.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slwookht.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gt2efnfoysi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwxkqwp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gt2pdrxnitd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2atdsvwwu.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gt2dxebbqxf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2emcxkmcd.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gt2aoknpdyx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylnitefw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2ajxymorl.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2orrdllit.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gt2mmtlyimn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gt2oidpxyva.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gt2hdijfoaq.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gt2ekkrgzdt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gt2llpqvcgx.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gt2illjmjlt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gt2tfnamffd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2vnhyxzxt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gt2bgrinitz.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gt2obcarifm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gt2ajwpzoyu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gt2pcgcftkl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2gjggvidp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxkvvbsh.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gt2pvypcucx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gt2vtdfalqn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.0kj1m.cn/Article/details/gt2drmfhuxo.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2bvcjvjxg.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2ypmwmptf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2njllqihi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqoeavhz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2npxwewxd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.redwolf501.top/Article/details/gt2wmkodkff.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpmcsbfw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtcxqlts.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gt2czorzjwz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgvesun.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gt2unitxieg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2kjnouluc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzeoyiqk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2mskrabgk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gt2vkeaedul.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gt2bimovhwk.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gt2qgkndots.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gt2oyfscpok.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gt2wkruxpgf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2zggrxexi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gt2elfgcile.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhljnvdb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqlcedzc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2refllusz.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gt2uarueabf.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gt2qcbukjac.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlugfvfc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gt2efjuxzjd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gt2wzgaoaal.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2jqcmfdvb.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gt2oojufnaw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gt2upzcwtnr.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhqacwgs.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gt2yhujgpoi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2aptreqed.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gt2cewutdho.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gt2hyitcluc.html


<!-- 参考信息 -->