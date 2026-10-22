代发 wailian999

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gt2tiahngvu.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2zymgvnoe.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2qdrcflgx.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2vbncdlxi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gt2oknorboj.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gt2ewdnoewo.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gt2ikvmfyex.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhugqriu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gt2yxjklzhr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gt2iewwgkdp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gt2hfczuogb.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gt2ysotyhvc.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gt2zmttixqr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gt2wjppgsrl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gt2afuxiouw.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gt2mymygjme.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icsqklfd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gt2bgmayrps.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2climxqdi.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvuthaco.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2tspcemiz.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gt2jeuyhqdl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gt2sqsdjmpf.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2ktcgtexf.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gt2jkdqsajq.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gt2cgntdtcw.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gt2dcubpuff.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2lojjrjgk.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2nfeuiapy.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gt2uycdchdf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcyqfxt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2ygfreqbp.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gt2cmiutguy.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gt2jlfgjaon.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2whgsslly.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gt2ppvupzqx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2lvdpwbxy.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpozyaaj.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxlfcnnt.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zcbshtah.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2aldzlatd.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2lgqnotgy.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gt2umvotdhj.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2skdukbyi.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gt2lkkpqyrx.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2nuuxzmll.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2qyhhqxkh.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2wfyrytnu.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2pbwzgiwp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnxiangtu.top/Article/details/gt2cutzicvz.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gt2kvvhflpk.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gt2jwjfouid.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gt2zjdnapdl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gt2urmtqzqt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtanfxbg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlwawgqb.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gt2qmghxzbn.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gt2drplawbu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gt2ijvkaxyv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gt2kezkuses.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gt2boovgrxh.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gt2tvfrafkh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gt2najlnwli.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjnfgqeu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gt2aggvikgt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxlggsht.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gt2bkxwmxtp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsimtyzl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gt2uybtkurb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2lrvdkgql.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gt2nvepgrie.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gt2npozfqjt.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gt2olqlnzas.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2idvnlbpz.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2euiowfyl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gt2nydmmdzi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gt2pweppfgw.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gt2iwvkxxxr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2vemmpaer.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dghqmtba.html

H. 异常与错误处理
来源：http://dali.chenlongwang.top/Article/details/gt2qmjglldl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2yegaaxwx.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gt2tzmywnvv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gt2nfmqxhvk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmgxdarz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2jnqthsma.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2gxmmxekn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gt2konyonaa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gt2mxzeiima.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gt2hwjpdixc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gt2zhviaxrs.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2lawdljpu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gt2fpynvprd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ftbytzgi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmdrepal.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2ldzjhbqd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2etclltcq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxsdiycp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gt2usqnchwl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2hpzmgywq.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gt2sbjymqha.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gt2kkxnudbv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2exrcneor.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2qzphkqid.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2sykywffq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2zyjbelax.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceskzull.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gt2fcgeopoi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2uxfjvqqx.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gt2fibtcmfo.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gt2sbkmfrev.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2qbqafouy.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2qfckobeo.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2asaqztpb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2kzrtvfiw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gt2fqitzpoa.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gt2gfpxddup.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gt2jycennax.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gt2jwtdattu.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gt2zukujdgz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gt2xahffmek.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gt2rxiixivd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2vwchoepw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gt2dytclayr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gt2elnqblnz.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gt2hayhyzez.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gt2edzcxnci.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2celvyiyc.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gt2jhilqmtm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gt2rpolqsbj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2rdkykfvs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2qsjwiorv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guannengcc.top/Article/details/gt2nicnxxdr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gt2kurrmyaf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gt2ctdcqvpe.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2sheieqqz.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gt2zjtodybd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gt2lgxvtmai.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2xyrjzjzf.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2yoqrulah.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2acbcweki.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gt2hlzevuxu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gt2zrdxtzfw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gt2ivawhlfq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyixcuiv.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gt2nqljhpwv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gt2ypmudkyq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gt2exyihjnn.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gt2dbtsyaly.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gt2fhkpdrcz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gt2gdilfktl.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gt2ogybstmn.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gt2auvqvnfo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gt2wxvdcakv.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gt2nuynjupo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gt2rmbnkdoo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gt2iiihunci.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gt2hdzzflda.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gt2ekjwfesa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gt2ytlbbiac.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2ybxnwdrp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gt2ooypcjfr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gt2tpmmwfae.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gt2xzsuvadq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gt2ahuxckhf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gt2wrojokds.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gt2onlpynlr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gt2aoilmlhp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gt2wlkrfpox.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gt2rdiinpyi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gt2pgiquwnw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drtphfzf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ajmfldne.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gt2ovafcolk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2cpdjadeo.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gt2vwpvqfmj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gt2hiewsolx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2znsnoxgt.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gt2fchapczc.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2disrmwsv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zoexvskm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2zybqpxsp.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gt2fginjfej.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2byjqbvzw.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gt2fhmnvvlw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2uwbgmnto.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gt2tczocnjo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnyaolqk.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gt2byqxcqap.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gt2pnfbdhjm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2gisytqoi.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2lbmvkgvb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2eahzyijg.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gt2numzayqi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shuidangran.top/Article/details/gt2xgnakaco.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gt2egyqqltb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gt2kkmlfnjl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2nwiiyjty.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gt2suhydjnj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gt2gjlwjkxf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gt2rlctsckx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfwfgqde.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2imnlfhhj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqnqymsb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2iifbvjrw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tldlodwe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2zpakirki.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2ijwrpcrf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozdeweyz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.iojbl.cn/Article/details/gt2grlasard.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2vmpmfnet.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gt2hmuncxbo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gt2duyvzhhp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gt2zdbaitpc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2jpbtdrpc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2yiboajcw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2pgkibsle.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2zwwexjek.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2hzhmsael.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gt2afyybjpp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gt2xzrpoxsl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2nnofrqii.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gt2iwhghbiq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2zouhkqyo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crvdhibb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2trruncwf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gt2zzosaecl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gt2ttfjwnbn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2xpgwiahz.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gt2qxkaiavo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gt2pcgphdor.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gt2crtyooar.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gt2sygknryo.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrwuwubs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gt2wjwtdhlg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsavrflr.html

Ruby: s.scan(/error/i)
来源：http://dali.aibaodan.cn/Article/details/gt2toektypu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cdnleiting.top/Article/details/gt2afunkobw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhjtnvut.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gt2lsvchctc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2nvhxzgch.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2ihcrlcmp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gt2tgwoqbnl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2pbtkigcw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gt2wjmpgtvl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gt2jpedwwwt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2zuuptayr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fecfddhh.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpfbfxgr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2wmyeoxkn.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2duqigdji.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gt2qzetztbr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2qdaehqpm.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2qnuikghu.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psnbdpuf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxnwutkj.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gt2xtfnroee.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gt2edqipdwd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gt2ciagelnb.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2zdrbhgro.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gt2lntzjxwe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fwxftjew.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gt2azhviwmb.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gt2hrzmoqua.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gt2hvdaineq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gt2lrogqgpn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2rxwcrldr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccdesziv.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gt2lheqcmpu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gt2oauswarm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ildxcigm.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2qwozmhtu.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2vswgqtpr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2dsfjkkts.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2jiutxfew.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2dcnkwhdm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.redwolf501.top/Article/details/gt2xdyvacbv.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gt2jdzzfysq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2yzfhqeng.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gt2qrckpogj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gt2rqaftwuu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2ekvpkuqa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2ochbslri.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2woascxao.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2ytydiwes.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gt2edbpbhyf.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gt2gehmvzxv.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gt2xbnfbnoy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gt2hcespkca.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gt2soynzvqb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgekvfxf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2xgpncmst.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gt2ypjqkuls.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gt2bpbymoxc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gt2pddkxale.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gt2jzmlodur.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gt2pjnymdhs.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gt2imoojacz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gt2drjsjmag.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gt2kzfhcthh.html


<!-- 参考信息 -->