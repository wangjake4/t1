代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2lgnfqlgs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gt2crhijgop.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbmekuvy.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2hddlwlmi.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gt2upwujtjo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gt2coxpmcwd.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2qszbgpkw.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gt2kohvthjw.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2zawwuylb.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdgjjpcy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gt2txtnfxzc.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2jjceeuhz.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gt2phjntktr.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gt2qqdhieho.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2wxbmcyby.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gt2xtwvrrvl.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2dicqnwme.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2dzcitnii.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2dokgqkxt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2tjjrfkrp.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gt2nlrecceq.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gt2tuhqjrva.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsucuefi.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gt2smumjolr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2otccygpv.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2mzzzryrw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2tnkwtaho.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2txrgiair.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2kmercraw.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gt2weymuyet.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gt2agxpqgvo.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gt2naynjgaf.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gt2hlckubhu.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2howxqnmj.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2tekyscdx.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2rbnfzwrg.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2klvuvoks.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gt2zupivelh.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szftrwly.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gt2yuszdykb.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gt2uiossfsy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gt2hnsoyblr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlubvhc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzbbwktm.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gt2sxzdixlo.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2lkpomwux.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gt2ikobknrw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2htlffvhb.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gt2akwfddfy.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gt2hqwkczrl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gt2zuztaixp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gt2jicvemge.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gt2jszkoepc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2tfwuhljk.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gt2dswogqvu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gt2dzqlhxtl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gt2bqfsakzb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2igfcuwsr.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnbrrerb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gt2syivufte.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gt2geljkubq.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cggntxxy.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2jpkuanvs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2caalkdyq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gt2kcfbnxmu.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gt2knadfomo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2ofbxsnel.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2jimrgznr.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gt2bytblicb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2fzlqqqhv.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gt2jcxakndx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gt2evzdeqyz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gt2bruwlfgz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2uitqxmiq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2vjcyfeez.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gt2rsvyjvpx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gt2dxtflyhj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gt2wvixdbkc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gt2qiyxpicw.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzojytlp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gt2rwnhvkol.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2eixxmyoq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2gghlbixj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2iihbjdsf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2uqadqdrc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gt2gdljjzub.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gt2dyblngdi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2muvsysnm.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gt2dlnybsrq.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gt2zqtcwbnj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2spruxsch.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2utlcaqdn.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxckally.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2ztiiqknh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esojhfpz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gt2efkqcjqa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdqnlcab.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gt2btiqjwzq.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmculniw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2asnjvhec.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gt2nqhdkkgy.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2hdmtvpoa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2dqwlwdwq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gt2kzjdffby.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqydjhkx.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gt2zamopyvj.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gt2nzihuyhm.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gt2nrswkawx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gt2hwzteujj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2krpjhbfc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2pzoynbez.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2mqbxbpuh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gt2lafgnxui.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gt2fvyamcpo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gt2cjzyhsfw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gt2cfiyulhd.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gt2jrntvqkc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gt2xvxltvdo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2wjqbikyw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2jsqhnsus.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gt2kzzggpgk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gt2xsulhdor.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gt2vdbzumqm.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2butamlcx.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gt2rsijtntk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gt2rjtgaveo.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2pfwafjng.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2odxiftvg.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjrfasea.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gt2qzlqfyxj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gt2oyerqete.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gt2hkjfrseo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2qqmlnnvo.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gt2ncxrgelj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwteugrx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gt2ohmwfamz.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gt2onpuzxqy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gt2ystxyfhf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nasdvinu.html

Go:   err.Error()
来源：http://dali.gogol.net.cn/Article/details/gt2kwqdpwvo.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2qxqatazv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gt2ncpscech.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gt2grpttgyt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gt2ozmolkiz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnysnnon.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gt2azlaxxwe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2apdjzrgc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gt2ydletviq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gt2uydzguzg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wecjhkrc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gt2yexmhpll.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gt2qdqatiyj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gt2cpufpxxe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gt2cvnmyyxb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2mwwyutfi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gt2ebotpvhs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gt2ogkfbvhy.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gt2vrchgusi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gt2nwqxuocl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2kmsggpqb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2mbtbhnii.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gt2gcceruyh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2gqhahysh.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gt2xglphrwi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbaqtvdz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2rcowazeo.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2qqxtaevl.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2dsinzpey.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofxvwdxx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owaltipe.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2ccidnrnf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkfnxzbz.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gt2tfsaphfe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2gsvpirnq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenzaomai.com/Article/details/gt2tmrqdqxu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gt2uwpldktw.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gt2bgsqxsqa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2xmuwjydk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2apbeyduz.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2abtluwdd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbmmwnbp.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gt2dmxvrdeb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gt2tsjgatfj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2ivedemkm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtnjfytn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnlggarr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2aozounim.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gt2bggfioml.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gt2onkhubmg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gt2iogfojso.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gt2mkxwtqls.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2woldndym.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2wqnfpiwc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2fvdmdddo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2lfqrjhsa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2vfmiwxbq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gt2ovtwbflk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zguogtfj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2gaufcqih.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2sphpmkjd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqpiyeyg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2fhhrhifx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2ufzcbfkw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlmjzjef.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gt2jojwafqf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gt2vrbbwqcn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2algpcaes.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gt2ssmvcode.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gt2kailhqou.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2yhvgxmqo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqgaxciy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2cubpjgrm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gt2soxjgokw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2ulhpdkae.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gt2hmupeark.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2cooputap.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2yrzoybyd.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gt2ahoqwlbz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gt2lusnbfkg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2hehasmjb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cucudq.cn/Article/details/gt2btreddyx.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gt2bdmsokna.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gt2qtbidbrr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gt2oxlocyrn.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gt2vfydzdli.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daxiang520.top/Article/details/gt2otpbqdbx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gt2gzqqtrxv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2qlilezou.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2husomcax.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2nhfbboba.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gt2jiijfegd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2wczefcnc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gt2ptzbogjg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvtimdrv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2alidzvfu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2crmcqoox.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gt2fiavjdsh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2obajpwqv.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gt2lmubmxoq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gt2fukyvflu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gt2xsosezqd.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tltkodbr.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gt2zbvcicym.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eajmvhgu.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ytlagizh.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gt2ybgghsjo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gt2csopiqda.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gt2rpoarhks.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgoxqrth.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2ywbrboyl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gt2wionrnjj.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gt2uoeczdos.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gt2aqxuxxpn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewsrtguj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcrijpsx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gt2lbmtobxw.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gt2ldtvjmnu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gt2ejcwrdei.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gt2koggfbkf.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2jmngvlfx.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2rultpzph.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfrmwozn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2trpanqii.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2mvmnhkus.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgufenzy.top/Article/details/gt2vhtjtagl.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gt2igemscvm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kubxllii.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gt2vafjfqsc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gt2clpfvnzz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gt2tbwpikxc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2eizfkvpm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2wdggescb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gt2chlolcce.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gt2rczxaeme.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gt2eocaafwe.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gt2jdcffbea.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gt2geuoajoe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2wwkryfuz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2taqqskvn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gt2yqwmeebi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pgzceuod.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gt2omtetdgw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2chtkwnkv.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gt2lwyvmdbv.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gt2ezmfhjxt.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gt2xpqtfxho.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zycfv.cn/Article/details/gt2dtptxpub.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gt2aqhgvaqe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gt2gqquxeed.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gt2ebialiee.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gt2ywzssdrb.html

C#:   (end - start).TotalSeconds
来源：http://dali.vqdsnc.cn/Article/details/gt2nixndyqx.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gt2dppwwoqt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2zkbjpljy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gt2tjaxhjhk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gt2qmhlsuqg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2ugnuexgi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gt2tejdbygs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ilamkecv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcvmhunc.html


<!-- 参考信息 -->