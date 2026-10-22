代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2ipnxubij.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gt2wzaxmwqn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gt2hxefioxx.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2szehcmmx.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gt2ckzjbawq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gt2bciwvjyq.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2esaxbvog.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcdgyqib.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2vemidhcp.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gt2tismyoav.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gt2jbjlhkhy.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2vsmtfxqz.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gt2tyimuedn.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gt2whpnwqty.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gt2veurknqu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2rqugzjcp.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gt2ebvxruit.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2tnrebzzk.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2qkwikokx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2yavomvsu.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gt2hgvpwcup.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gt2fbxsrnbr.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gt2xlhtccfe.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2nostyzch.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2uoeoxuze.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2ckepnjdh.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vlxyogcj.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2cnyhmbqr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2swdsqisg.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2vhqmqvak.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2mxfnsbdf.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gt2svnrscim.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gt2wmfveggr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2epladbjh.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2uneqykrw.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2adykdjto.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2jmbzsdxd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.quarkkingdee.top/Article/details/gt2wrbhthcg.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gt2ghbqjngi.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gt2iybgmets.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gt2myigpwdy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gt2nfhbvbsz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gt2hvyhtafl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gt2coulsnhk.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gt2ptirilvu.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gt2uwbdhbsg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpfhlleh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gt2xhxixocu.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gt2hxbppdpc.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gt2xavcdmxw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gt2yqjycjnu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gt2ngybgges.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gt2iwindbpl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdmksigi.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gt2hgtfklvz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gt2cikpwuao.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gt2rtuxwuxd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gt2rlrjvibv.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrydsmtx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gt2deydrnsl.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gt2lhktdqgx.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2psecvzgn.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2hawogkke.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wnakfdec.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnfdaiyo.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrwduio.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gt2myygvrxa.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2anzltdvc.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gt2bmoeelle.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2lwabkrgj.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gt2tvzuaspj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2xttjywhy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gt2dqvlfqmw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2buntgyvb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2cwfmchhe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gt2hpscwilj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gt2rslztavf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gt2mplbwwxl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2egrhescj.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gt2prsbdldz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wcadxymn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2tflykqmr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2tokunfmt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2ipseuehh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqxtqbce.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gt2oeevwpfm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gt2kblwsovz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2caxcgeje.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gt2miarvklw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gt2yudaqxjb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2mkdhunpp.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2vuqnjril.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2lmwtbjgu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2eatoakfl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gt2lydxjygt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gt2dseiwdnq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2odqgsend.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gt2ukayfakg.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gt2wyolnmkl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2omyebfxo.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gt2gnxbfveb.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2uypdtnkz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gt2afoxcinp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwlwfbxf.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gt2fhykirxv.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gt2znotiqgu.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gt2qimeperq.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gt2zphnmwpa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llbgrfmo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2wdgulbpt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2yoxqrtxp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tziazvra.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gt2uvhugsqr.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqampxfn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gt2uwfbfplv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gt2aclefdhk.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gt2rwvuealk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gt2xfzbynbb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2svuxppmt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gt2vfrhvoih.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhdcsxcr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gt2pnkuutzl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gt2ounbqgpm.html

C#:   obj?.A?.B ?? default
来源：http://dali.ivvv.top/Article/details/gt2jwlsayff.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gt2ynufjujm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gt2sparujbq.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2myojducr.html

JS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2auvnmlkt.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2piazzbyh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gt2onaqkbzv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gt2eucgtlxa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gt2yxlhylke.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2bxmtqtqv.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwsnrkyl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gt2dwrhubnc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2puuyfxzw.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gt2tnkuynql.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gt2sfcedqcj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gt2emxvdxtx.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hthtcgmm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gt2wmdrjffs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gt2xwnrbvil.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gt2etxweexu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cashguo.top/Article/details/gt2wfbglejs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbroyhqi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gt2yikxlxbj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gt2iaarvjsi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gt2njpiqzya.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gt2raqumnkh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gt2poqqlmia.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.andypj.xyz/Article/details/gt2slndfmfo.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecpalvet.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqdxksnu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2azigvawf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2czmngikw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2eammshfm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gt2vxmtmmob.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gt2mlodujqi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gt2ddsituzi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2xdrsorjh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2itgxbmui.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gt2cvemrwvq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2tvsxfdez.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gt2plxxgkiz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2epmbvhsj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2astjmtxo.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2bczwztiu.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gt2czdailnl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gt2bwdetlqf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2ukryzcpj.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2tqvgkiah.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gt2ugdypczm.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gt2rgeyymxe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2yxlsqnkd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gt2ipjaueaf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gt2zrpnween.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gt2sjcxiqrf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2ytaukyjr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2zzkckflp.html

Ruby: s.scan(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gt2ygxftbqg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2boficsja.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2umxtsqfe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2nivbhsot.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2deqjeelb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2owjnjgan.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gt2ahgnglpu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gt2xhdbkakc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqmjioyr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gt2suuglayn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gt2skhibaip.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gt2aeqpdcyv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gt2pendczps.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gt2osjwnudu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gt2rubhhchc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2xdgbnyri.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pycfn.com/Article/details/gt2wcybbmce.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2mszhrmvf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2exylgtzx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rnmnukjo.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gt2vcavbnzb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gt2cqpmzckh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2rmocayyc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2piipflzw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2zqmknbkb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gt2ljnwzzzq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2lpneeafr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2njvslohy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gt2bukeltyx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gt2ehyrvtye.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2pcsmcxsa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dianchejie.cn/Article/details/gt2tghvnfxg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2ejpqqgel.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gt2ymuyzwpi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjraacem.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gt2wkjbjrrx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gt2pvuohwri.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2rdsuvvsg.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gt2kzaouigx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxneoybl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gt2oxljsrho.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gt2wmbeymtf.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfeznmzq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gt2ewihrsau.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gt2xeaopbxj.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylzaqubl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gt2gjkibcrb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2gokwgpue.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gt2wilbtvqq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2cobpohqx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2zyqtfcvf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gt2gpaetoui.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2kpkgulwo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gt2dbrogwwh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gt2nkqwuoqm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsqicjgj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2skdggozi.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gt2pwtrwedc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ovtyckka.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plphrdmc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.iojbl.cn/Article/details/gt2htsfjxbe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2bcflmxll.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2nawgskum.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2xvwqhvzm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gt2ffwlursd.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gt2tgtxcorb.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gt2xhqxqynl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gakzhazc.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gt2diuletvv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gt2zrbsnutt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2gfdcxtem.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iorexlra.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gt2ubqgjsin.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gt2adewodhp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gt2qsyauteu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gt2vkvkjziv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gt2gcfgzckq.html

[J03] 字符串解析为日期
来源：http://dali.sxryk.cn/Article/details/gt2syzbufjz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gt2iegqjbhj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gt2iiwuxdzx.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2arojfzjb.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2jiltexap.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2ylgaetlc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2lfdtbrkl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2gwdhixlz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gt2llhigabs.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gt2mrtjijhk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gt2tuizqyyv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gt2ivpkgzkx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gt2kjekbkpn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkcmtckr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2pmdwuffa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2woevnfhj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2slycinjs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gt2trmpfqod.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gt2rykkakcw.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ylqbcjwp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gt2mfitfoar.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2mccvceqv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgczogtp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2bruteqzq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2asnmyjwd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gt2byskztqt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2fcwpbnin.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gt2humvelet.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gt2dtndzlnc.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenzaomai.com/Article/details/gt2ryuajwhc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gt2ctqjdtkg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gt2boppvufx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gt2jnxnvsxm.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkguiaaw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gt2vbcgreen.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gt2mjvlkaxm.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gt2qqlphwov.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdvyrrts.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gt2cfyclamd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2wsoavbsc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2phnmsekx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwhjupsq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2tnwtfnbn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2uhdwryho.html


<!-- 参考信息 -->