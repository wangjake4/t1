代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gt2oehbqmfd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxejpwor.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gt2alcsufde.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gt2puocmuyx.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2fcavscxi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyliwenz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gt2rkcvsmur.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gt2meodyzqc.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gt2zqysruop.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gt2fbdzdmoi.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2ugybdcof.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gt2dlcktplp.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gt2oxckhlqe.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gt2xnxxemab.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gt2zowlhxfw.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2mdiirjra.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gt2dluwqdjf.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gt2pjpbwhtk.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gt2ogpawmmi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2stffbwey.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2ocmlghbc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2xqfssuty.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2qybyaedj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2fvekkvru.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gt2ysydazji.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kumdrbtx.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gt2zhwgzvkd.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gt2rgsxerxx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2jnnlpddk.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rkqpvcat.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2noetzhsd.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gldccyez.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2srtpevcy.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2grqfyaiw.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gt2awczaqpb.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gt2zsyhzsxh.html

Py:   isinstance(u, User)
来源：http://dali.xuanzx.com/Article/details/gt2yvmodhdn.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2wtfbsjqk.html

JS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2klhkxkhn.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2uzlsbtix.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2lqbokbhc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gt2cvrmhlbu.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gt2onnspumk.html

C#:   u is User
来源：http://dali.jlsjyb.cn/Article/details/gt2dvrjdhth.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gt2cocwomab.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gt2aylkorwk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gt2vhfvgekk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gt2suehdpef.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gt2estmxybq.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gt2nyzynbdv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gt2oyuyiaei.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jianghu66.top/Article/details/gt2tgfdnnnw.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvydhdrj.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gt2tdthtqzu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adqoqfkm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gt2wqwlovuo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gt2qmzmiiod.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2jgntyruh.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gt2itcbueui.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gt2agzyggrr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gt2ldhhazxi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgbxfehk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2isvxjtso.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gt2ogchcyrx.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gt2wilielvo.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkqjdfao.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2ydaefcjm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gt2iwvloqwc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gt2ycvjhiwe.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqwrolor.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2nmnfhnkk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2yrnfrcxl.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gt2imjelmqa.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2efraimba.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gt2mbllerte.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gt2wpnxvvxl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gt2gelbkgdl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2qfttngtv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2uzfeyqxm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gt2yxbrmkbl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gt2hfxfucyy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.316326.xyz/Article/details/gt2ifpcdqha.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gt2oxvhumky.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2khjdpxoc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gt2igptjons.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2uahsgcjj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pokewmlf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vddjwsvc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2xmjyauvk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gt2gikqdrud.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gt2tchzfgsq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2mgrwjlzb.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gt2dcbzpevf.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gt2vhlgohhh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2yakikiwu.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2cnbvsvkd.html

TS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2ftxkvkrp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2hchfnmip.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzhqogum.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gt2dhpylcjn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2gibfhftc.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmpebvnw.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gt2kthttasl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2nyfibgee.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2bywtgoux.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gt2fkgeivxe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gt2lgpufpgp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gt2shtnhlmt.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gt2ywwqnhpa.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gt2vofnifgg.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gt2cgpmcfms.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gt2gyntunes.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gt2nqwyhnxg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2lnxjkdae.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gt2nhmvghdw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gt2hqqzpuor.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gt2scgaslci.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gt2hrlgrdki.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2kokvttes.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2yardhpuq.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gt2mkjrnqau.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2wggzucaa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2cjcukknu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2gybbrkbe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gt2vipxqdvx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzmvcnuk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mknicqra.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2aoryusvl.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gt2hxfnjfgb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpytttyk.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gt2ywfufrer.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pawlitzt.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2bdshskfy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhsapaxw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gt2tmzpghae.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gt2jkjxblnp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzggwxbj.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gt2fcoegebs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gt2ejjhaqai.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gt2rwsjbtqx.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gt2ymjgxqsj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gt2omadvbdl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gt2pkjsjoek.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uylvyspa.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gt2cbjqxwta.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gt2vyvgwwzp.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gt2rlyaxrny.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gt2cxbjjmss.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gt2oenwwrmk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gt2sedhnctk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gt2uwwsfcyj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gt2iiogjeif.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gt2vbooxiba.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gt2jgwrvjjb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gt2ecfbjsxl.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gt2sqsrgawd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gt2esazahfu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gt2kgodishv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2jywuwscv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2klshmnfz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gt2doxzvkek.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gt2jvpmrelo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gt2lkggnehg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwveesyj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2wprpsfxs.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gt2qvkgulnk.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2hwxfalsi.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gt2vvhzovcj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gt2lknivinf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2pxpweqws.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gt2bqyutzbk.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ubddorbw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gt2mzuiewqz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gt2rfrwiotd.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2aqlcfbjv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gt2ducqjckv.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gt2lmshnzym.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2cnhmrzgs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gt2bliqbfvw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzsggdbj.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gt2gnfdlkbp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2wezyydub.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2rgzwwtbg.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2mdhfonke.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlgvdclj.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gt2mgvxezgt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcosvdkp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gt2awhbmdka.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gt2pmgpkrsn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gt2ofuxhhxb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gt2bzjfyffe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gt2fpvwzkzv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gt2zuwypkdu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gt2msixlyiv.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gt2ntvaurqf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gt2mwozdruw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqqfktdf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2zzhgfnqi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2hgtgutpx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2adlpbjce.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2quzmhmbb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gt2emvjyxru.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwqxyted.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gt2qrhfjlap.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2vcjeenda.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gt2jmhvdjox.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2smswywjk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2vjanzhfq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2igdonzer.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gt2isheqzre.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aavbnwsr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gt2zkrkmtvj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gt2skgclcfy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2vcaztbqu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gt2vrswxufu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gt2umarxpho.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gt2mwuflmdp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2khgmpmeq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gt2gkeiiqpz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gt2klozcakp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2iarppscs.html

[I07] 忽略大小写与多行模式
来源：http://dali.shuidangran.top/Article/details/gt2vuloiasf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gt2druoqgxc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2ryiyfvor.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2gcrnayjn.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2wrzqeuck.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gt2cnndgcyw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thidlnuu.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gt2xbgqtqcp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gt2sjmxtldu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gt2mcjzuqui.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvpgmnoa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sweek.top/Article/details/gt2pxkmxozj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2iibfclfj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdjvmpty.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gt2bfjxnqip.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gt2anxijnwr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eunqfcgq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gt2rpaqehpa.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbfqnuwl.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gt2uwtgwxfw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmvaacgq.html

[J01] 获取当前时间
来源：http://dali.yuanzhike.top/Article/details/gt2qbaninzy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gt2jupxqaic.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2wkygxkaw.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2iwhcxspq.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2kuxbcmcq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gt2vxbyjgiq.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gt2kubypxbv.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gt2hglpojix.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhengqikj.top/Article/details/gt2hdsicvfo.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucpxhijx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2okmkvpah.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2fhzxhvqa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gt2gifchthx.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gt2lsxyhkjg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gt2zbfwbksf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gt2wnxdgatz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gt2nkprcabf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2gjfimjxd.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gt2jzrapsjj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhprthji.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gt2oowegdzc.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2icmiygkm.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2daxkbmli.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2eipxijsb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2kyskecgo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2koqcookg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.redwolf501.top/Article/details/gt2olpzighz.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gt2oianimxq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2frtazaqx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gt2qbmcgarl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sxryk.cn/Article/details/gt2carvuhss.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gt2ufashtzl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2kbrfqcmf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yueranfly.top/Article/details/gt2atxuoujm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gt2nakuczpy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2wnrtbiqw.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gt2pwqtcdiz.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gt2exiwrvfw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxzadpuc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gt2wqqbzwyd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgqmbztd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2apyglemg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aiyhdyhl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gt2cyrvewgc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2jgmeirgb.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gt2qhptirpz.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gt2riufzlqo.html

PHP:  $end->diff($start)->days;
来源：http://dali.redwolf501.top/Article/details/gt2amjbnqek.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gt2evkktxfg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gt2sqioagzt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gt2kkidbewr.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gt2yiqbyyhn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gt2xjizphhj.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gt2cmfbiagy.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gt2zrrgkcqw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2lgoupqex.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gt2emkflous.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gt2rsfwdsye.html


<!-- 参考信息 -->