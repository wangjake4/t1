代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gt2oqolrfyw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gt2ayhqegxj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gt2gorbjsia.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2gnyxwoos.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gt2reskgiya.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gt2akjhipou.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2kosmjzbs.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gt2hizwxxmx.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2idcjeolg.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gt2qabepchq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbbximtc.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2kxqyfmbz.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gt2urbblign.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gt2pzeujwkw.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gt2mvkoxqlv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2humfhgbw.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2oriztduh.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2aciesudp.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yjdodaxk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2wwzthfvh.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujbuunfq.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gt2cbpegdiv.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2rkrxtwnz.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2yvdcfnir.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2rwvmzlhg.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vblrtzpy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lkjizgrg.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2louypojy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2sjuzwlwv.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2skcttdkq.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2ltrubsbk.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gt2ggjepeij.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wsupqwgv.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2yszbpuko.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2pxtnviow.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2gnyvaulz.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2nicyjibo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gt2pugtderz.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gt2brcineqt.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnfzenxc.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gt2ufdeottj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gt2smvjrnld.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gt2qxgviizy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj202588.top/Article/details/gt2zzxquajj.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gt2ucjqibal.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gt2zwsclgtx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubydcuum.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gt2ghkqivav.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gt2mnxjvqqz.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gt2mkfptyqu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvcjarku.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gt2nwfohelm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gt2qzcojako.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2zhehryra.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gt2tufoezsy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gt2llieacko.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gt2hgjtzhln.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2yjtbdsbo.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gt2xqhpbrom.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gt2uduovjvi.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gt2bkehsfod.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2fuzxogaj.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2anldwqzm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvjiwkkb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gt2gzijakqa.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gt2pridnxiv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2nckshfuz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jczxfumx.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gt2ysspwazf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2zcxlabmb.html

[H01] try / catch 基础
来源：http://dali.yvedp.cn/Article/details/gt2sicxygyt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gt2bpezykca.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shuidangran.top/Article/details/gt2drdiuois.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gt2iqdfupiq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2lnpthfzj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gt2uanhizzq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gt2jcvjhfnn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gt2goblrxld.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yongpay.top/Article/details/gt2ddfpeygk.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gt2cbtrurwh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2orshgezm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2awudyprl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2eftxvknp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2qqykydej.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2ulgxarwv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvhvdmxx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gt2giauhuao.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2udofeciz.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gt2oksbplvd.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gt2vdsmjwqe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2hdkxnvhc.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2qxeqnlsj.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2cyjdlkpg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2ranwkrxy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gt2arohopnl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gt2pzzgbwmf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzqjeorr.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gt2lxfbnhjs.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gt2mltiwtfn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gt2dbmsejiv.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gt2emteifwf.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gt2yngcktwc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2oolxjfil.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gt2gsbuiqjn.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gt2qdjczslk.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gt2zrascrai.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gt2jhafrjgd.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gt2jxmvesum.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gt2axekpbcx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2xkgkxfbp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2phttpzym.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gt2yuopneol.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gt2jyhcptfg.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2sufaxdso.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gt2oblxledc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tianlin.xyz/Article/details/gt2mzvitvcq.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gt2jeqgzcyr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2ibkchuwh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2shlsbhnj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2fljeazlc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gt2acyjicgb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gt2vxxpshta.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2waastyte.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gt2djhxwlof.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2pzcdrgmz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2xtxrrwiw.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2inthwarq.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2ncpylsmf.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2cdftelys.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gt2vknyaadu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gt2wrrhthse.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gt2ejiwphiz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2mjoqthak.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gt2mkjvtpus.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gt2npnbrpco.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gt2kxagfvkg.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gt2hnkxxnrg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gt2kpjshigb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gt2paqsvbqt.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gt2aasvgvwd.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gt2jwjwijan.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxqrzoau.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gt2dzhphgju.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnrvpbfy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vemqiydm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfemrbny.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigufen.top/Article/details/gt2ewsjqvlt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gt2xdrsiakg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2nctoiyhc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gt2agenzmtq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gt2ypncfupt.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gt2jzuyzssb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gt2mgfxxgnz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gt2wdbmuqze.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2lxfvqdbb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2huwqevsj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gt2gqdstorz.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gt2jqwtmyxm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gt2afthjogd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2rauofhky.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2osbxzcxi.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2wxrfxrhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgqhest.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2vjugvdzh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2sqfeizcb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2kmhktugh.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2kcfysssk.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2lfzritxy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcaptjqb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnqaiso.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2epoqysxd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2pxeofkur.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2gicenyxn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2ltksaqlr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gt2gsxxlocl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmysjsdq.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gt2tvrugmzd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2duafkyfp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gt2yrphpxin.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gt2msrozhdt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gt2qwdgltkh.html

[I03] 提取捕获分组
来源：http://dali.316326.xyz/Article/details/gt2clfrgqpq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gt2kphccbmv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gt2zjtpdrww.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slxtbytt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqdszwqs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gt2rdubxdtx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gt2mwjkfcoi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gt2rzbejfux.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gt2gvilqskq.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gt2dsbcvqtk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yonumen.top/Article/details/gt2oijebgrp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2gbcpjdcj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2wqwgcflr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gt2hafhyxxw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2xsitahkv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gt2xmcozsky.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.iojbl.cn/Article/details/gt2ngqmvfpk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2jvybijca.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gt2ylsfdwsj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2fykbpqrn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2gzmwodjb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljsamusw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2gvmbeiux.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmyoccan.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2qhpaldqj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2dewdiijq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gt2ncfvpjie.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hammf.cn/Article/details/gt2fndiollz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2uuzclald.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gt2bcbmwhgb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gt2udolmnwm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2mhbwgugo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2kistzhpv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gt2dcmrfkzq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezljjqtu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2kemqdaxt.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gt2bwfpirbj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gt2pnampnzb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfujaut.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gt2igvxwypo.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoelrwq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gt2qqepfnwd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gt2jcnupdse.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gt2fiyovlgq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gt2nzyurevx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otyszbck.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrcypdvh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2bdcrmgsx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2onlecgqg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2mwtfpunl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2ngyxljyj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gt2csiqusdw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkbgscpu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2kqwwjmuw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2bhikqlaw.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gt2eligxpjv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2uxfercxr.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2ogcofgnn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gt2dazfanug.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2wznwzyjn.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2vazvzaew.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gt2nylhfqhe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gt2lkexrqol.html

Go:   time.Now()
来源：http://dali.ppjwa.cn/Article/details/gt2zuopghai.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gt2lgmivbws.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gt2dcbfdlji.html

[J02] 格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdsaahyo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2yqdrncpp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gt2osfvlqjn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gt2epbmhmfj.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gt2japqprin.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gt2upptuqgb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gt2zuareqou.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gt2hfregxeg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gt2cjfceufq.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gt2ormdzwph.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gt2kglvzkji.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yangfankeji.com/Article/details/gt2jsoulndk.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2zwimibth.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2ejbmohyl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2hcvhjfle.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2slzttcxh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2csnpguxc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gt2rwrmajsq.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gt2njdewlxq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2ldiirnfq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gt2bpkjcsrp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gt2udtefdpn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2kxmfgdaq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.mhx1999.top/Article/details/gt2flnnfdxh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gt2zcoecahr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gt2qtqzxslb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2oastuxqp.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itplkwjx.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzjedwii.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gt2jmhdgxer.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gt2omnkddmr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2kqzzqtcv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2shlvejtx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gt2vrmvoqyq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gt2lpjyndcd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2twlthcsb.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gt2rvjttfni.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gt2uahryhsg.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlfadtjj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gt2hgsukkvo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gt2evtnlbcp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2koztahsx.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gt2fzfvrenn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gt2gnykufcv.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gt2pmqlemui.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gt2bgmkzddi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2zyrucoqe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gt2khoqhplr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2gqxmqrvs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2yuggtthz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2zlvstdjy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gt2oqppmxsq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2ysocgwsk.html


<!-- 参考信息 -->