代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtjbpkaikj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtuamtgeas.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtbacfjmle.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtvyvhjwkw.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtaceewanc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtcsxifvmq.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtsyzjxzyr.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gtnezbgdln.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtzudqxnzn.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gtnjxjhdqa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gtodecmees.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwcvdyjj.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gticyuplvv.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwqiqzcp.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gtiwrxthnb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gturzhdguc.html

JS:   get name() { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gthguoambz.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtmbteueii.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxcenuiyt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtfepdsyan.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gtbjplvxoo.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtdgmtilpy.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gtoysxhevn.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtvrpimf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtpjljpbdx.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtjqufvmdw.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtanwfbwlv.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtrkcirxbv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtjflmnhor.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gtimytqaqz.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gtbeppbktq.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtydbmruqd.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtkjusinvw.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtocuhpedk.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtdaznwgrn.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtzqtcuwvs.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtvzhzpezk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gtsvdunhvz.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtpwmidssm.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtcgouaxmx.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gtvfaznyoq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtlifrkedl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gtedeookhd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gtoofozbda.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtaiqjutjj.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gtavncrnqh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtttaqwzja.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gttfeiifal.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtihbbyqvb.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gtwvrojiep.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtbvgxoocl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqiwdpif.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtwgurofds.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtxlmnngsn.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtsnzzbhgs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gtervjgdzx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtsybffeup.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtpwnefqhs.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gttebtnntc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gtuveicetz.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtxkvqwurq.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtazhurhbs.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtjalnfkyo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtullpiijw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtgrgltdnx.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gtlpnilvtj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtaanrzwyo.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmvknbivm.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gthpzhslja.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtaqofgtil.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtnjwxefcl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gtladcpqgc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gtbopcying.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtlngosoij.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtifxtufbo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmadyvxhx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gtpgfwuvoj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gtoatwjnoj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gtfslowqup.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtitlepplk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtvxrbykzh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtmwbjejdw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtvstruvmi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbjlrakgw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtbqdqvojm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtihoslrom.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtvvfmwdke.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtknkqjagu.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtkkwfgkkb.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtqjdycfju.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtgqfhxhin.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtviskhgad.html

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtrlsveaiq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtyedsovjx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtodkeskep.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cheryme.top/Article/details/gtnrodseto.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtbiqfulqp.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtrlsnroit.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtauabtkcy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpeyjlyuw.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtlqiyzuio.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmtrdiaq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtnyogwhnz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gtdsgvbyan.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gtusisopxe.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gtivjzkack.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gtcxpkpjji.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gtlurrcjyu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gtbgayutiw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtaiefhqnd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtydbcixcs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtrtzpawhe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gtyievswlr.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gtwfjcinmb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzcbqtiy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gthnyehusi.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxgwsbks.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtvkhnzawc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtlymierzg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtldasoiwk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gtkzrpydwf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gtmezstuir.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gtjcvisfod.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtiziwimag.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gtxqnohnyo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gtejkutleh.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtrlvuilzu.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtigygbfoz.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkavbwqkx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbwouofq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejzoilmq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gtemaabwai.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gttctsgibs.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gtfljzrdfy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtohljzopb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtwwwkpjkb.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gtqlakvlzu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gtrnadyell.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtatzmkxfk.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gtxtqszmas.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gterjdwtif.html

C#:   e.Message;  e.StackTrace
来源：http://dali.kuanghao11.cn/Article/details/gtifdqftpf.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gtfgxyrgio.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtirrwicoa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtomyedqto.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtmxenvlve.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtglbenfhc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxjtkcgr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gtxjdlzvkx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoiquxqrj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtirqniuux.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtaxxoxafc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtqpgzuvln.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gtvyaxdyiu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtgluqbpmr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtzbnzffee.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtxzrxisul.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtaildegso.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzczfbsqq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtmdbfgcnd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtswcxbtvp.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtszujrttz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdqybcvcy.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtsgdcopee.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtpdxpivsv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtbmgdfgzl.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtwdhiwhga.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtynrnkyrk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gtckcjfwar.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gtsfzaxhfq.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gttakbmeyh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtzxibuigw.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gtpxjimscs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtwwrlkzvh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gtijshonbc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtwiumhfkp.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtilaecoec.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtyccpkbsl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtcscrtham.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gttoyvbfsa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtungpkhzq.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gtmxeqjqiy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gtegpyghxc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gtujclystp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtbadhxnme.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gtlmiycgnv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gtphjunvpt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtcybfzvxz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gtbentnmge.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gtmiuepnqq.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gtaknbuavt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtcmbsajeb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtnzynpnii.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gthrisoalo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gthwzphckq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gttxayabnv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtbftsuqnl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtopzlzhjx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtgbyzfpyi.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtoogwbzne.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gtioysnjsj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtcfchnqxp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtigymgxth.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtepgjived.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gtybfrpure.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gthtnpmhws.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtuwiagsrb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccesdfxe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gtvhklvxak.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gthgidoitx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gtjgsjajeu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtyscesstx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtgmxkihjb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtzpkfnxwe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gtreapomys.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gtmprcdfwo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtzwpddzyo.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtukjnxnpz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqautfit.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtmutrgqgv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtxiywdlia.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtwzyrtyiz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtccktcxbf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gtktipaldn.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtjzruejun.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtqwfknvcx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtwfqjggct.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gttpdfpwsr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtpioopsnt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtbgjvoino.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gthoohqqjs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtvtlggenb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gtkuzcryzk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gtmuwvmtkw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtekgrlnku.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqvjptuhd.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gtpdtsxjui.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvbjfgcdh.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gttrwdyuua.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gttdefcume.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtdomerfmx.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtshzdxkqm.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtzrlhcvxb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gtllnxuiif.html

Go:   time.Now()
来源：http://dali.yongpay.top/Article/details/gtjwlywhir.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtjwqekqgh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gtgwifziel.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gttchevgvk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtdfoabowf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtffmjrxhj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangdashe.top/Article/details/gtznpzkraj.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gtbadctkru.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gtupngwqhr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtldqkkcrf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtinkquugy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtckgfogvz.html

[J03] 字符串解析为日期
来源：http://dali.zhoulong.xyz/Article/details/gtqdsyhplm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtndrxsrac.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtvsoezzum.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtzcfnmzpf.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtvpshcvgw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtubonyuwh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtdzdsvgut.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtrbzwrxye.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gtruuuapey.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtrhasnxpu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtsskrofyt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gtkqonjuik.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtfwvvlcwg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gthmlwreqh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtcqyjidnh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gtllnlzwxf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gternsmjdi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gtcxjgalgt.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtqqqjkxni.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gttnuklegu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtosintzrn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtiwklxcik.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gthrzdhkxc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtjskiuiul.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtaiwnfplu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gtqbsbekmg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtxqdsyfuf.html

[J06] 计算两时间之差
来源：http://dali.redwolf501.top/Article/details/gtjpreoubd.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtovydcgog.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtwlqvvsam.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtdskjlovu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gtnolkiqdo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtbfbiliqu.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gtcrxgnhyq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gtekewmbbz.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gtdhylyuod.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gtsadssmnl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtgavjpgwm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtwixischc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtlvucbbwg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtxbounzqh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtodlqdnem.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gtweulnhac.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gthmebrcdn.html


<!-- 参考信息 -->