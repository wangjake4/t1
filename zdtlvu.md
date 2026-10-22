代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gt2kxdeebgg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gt2kkjlugeh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gt2neiadend.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gt2fmlpbefx.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gt2ajdzihek.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpqngaaf.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2ekclhyob.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2rhzjgqbs.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgfvndfb.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gt2vqqxbftb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gt2nsutwwbl.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpoyrney.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gt2yurwrjgo.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gt2vxikkzgt.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2cfyyimiw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2wlfmpkzs.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2dixzzcsu.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gt2crsbtvth.html

Java: public String getName() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yobihgct.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2etczcepi.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gt2aqknfglh.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dyyraaut.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2qtvgfhdg.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2spkxzaoj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2znqfcsqc.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2zggpltat.html

TS:   toString(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2jxbdjwie.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tehbovvt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfqqndpv.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugeotiez.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2gulpmwod.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gt2iaqnqmsv.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2bsqqrrly.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2rewqbrdw.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2hmcjtmfa.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2cmfmfllu.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2afszuqiv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gt2tpmjawck.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gt2ndoxcaly.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gt2xvsxdhss.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gt2lysufvgy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gt2bujuwwvp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlzxjbka.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gt2ykfwsquq.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gt2avmvyeht.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2deqiradp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gt2cbhseekr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gt2iisucqob.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gt2vkfbkclk.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gt2dbidotzp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.0kj1m.cn/Article/details/gt2rtthnypy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2znzncibw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gt2lzepedxt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2ktcliejk.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gt2tviiqiqq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gt2smgudngn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2vxuarhbf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2zaxpliri.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gt2ggthnjcz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gt2zipygzfn.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gt2eqipgppx.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2wycytcvb.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gt2mhjhubvs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gt2ijkipngw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2vddhnesc.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwubvtoz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2pnltstdx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2tdgdtvvx.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gt2nxbaevya.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2wlvaqpai.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gt2avrqybxp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uitpedur.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zczygatv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2jpkhymes.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ueteebrs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gt2bszvwqur.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.havefunace.top/Article/details/gt2llngyebm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gt2mvbozzbh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gt2strgswbc.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2usqlcxrb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gt2nlbhcixs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2ejgggluj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2tzwcvclz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2cxiebnek.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2fqkwpuyh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gt2cwpyagbh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gt2chqzwdjv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2jorlamls.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gt2dgjhrguv.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gt2ilzevirr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2fiitcwpk.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2wzkwpdzt.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2quhqzdji.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2sjralmdv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gt2kgmgkjhr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gt2zqqggidc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2ifqaktpn.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gt2eygrphtq.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gt2kvfclsmc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2hahyktrh.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gt2djtnzdgn.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2yygwakyc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2sohauxni.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gt2mjawvstp.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gt2nmrevyvw.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gt2bmrytqwc.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gt2itdfawjg.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gt2ekklxjpv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cqqwz.cn/Article/details/gt2hzrnnnxf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2aizkerkn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gt2ssempkyp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pengilpz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gt2iqksmlpy.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gt2vevsizoh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gt2lchjosch.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gt2uoiwcwpl.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gt2efgssfhi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2sserlpbu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2aidipvkm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2qbkggqlw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdedfohd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gt2ytktdcre.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gt2ozdawlic.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2psbrnjma.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gt2fmcvnxua.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gt2haarsxvu.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2tigphtfa.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2jeuvwggz.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnevrtiw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gt2mtzkebmi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gt2mhvcvaep.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gt2vppkesds.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orrwlemd.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gt2qcbvmtxl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwwvntrr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gt2mtyctjic.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gt2ncwawodh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gt2bvnahwmg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gt2zvleavzw.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gt2denailff.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gt2vyqoxqvk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gt2wqrqoeot.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gt2mwjwakvl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvslbkaq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2tahcnzsg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gt2xuxnipor.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gt2njjcralr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gt2bxmrkbhs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gt2qzwaydkd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gt2mndveluj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gt2musztvwg.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gt2pzchbsxb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gt2mnufgioh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gt2lunwipcc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2hezdandt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gt2bsakepug.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gt2lowsqkfu.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gt2gjtommnb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gt2yaciagdo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2xuricmpx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2llqytypb.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlwsxjft.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2tclrvmqy.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gt2ttiknwqm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gt2gdxyigsw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gt2ppaymzgf.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2fdfdtfup.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2qqlceate.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgikrfqt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klrupphk.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2uvlgksif.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gt2ztxlxabp.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gt2wrirtliy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2ievmdwug.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gt2pxesiira.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gt2rwhfrasm.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gt2xofldgnr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gt2moqclzya.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2ueawjizz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2voczvpyz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gt2hjtcewhd.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gt2uatuxsmu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gt2crbcruii.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gt2ordsgaua.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2lydmszjr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gt2vxxvukyz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gt2ylovkouz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gt2qscexpow.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvlqrmiw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gt2yvgorogt.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gt2nriwzbxy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqfukmcc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gt2ijevvjdv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyozwbqi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2zfafpmkr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2lmflinfc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwnnlfed.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gt2aqqtfaiw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2rwikknst.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phfvirzy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajhfqznb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2fxxuagsp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpackmtd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2zshwefhu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2efzatpoe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gt2zptszmnp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2iuzpaima.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2lvbaznvp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gt2jxjraicm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2jdcsvadc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gt2aygxawtc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2hfefhree.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2dhpxnnfq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2lfhnvymc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gt2dvaehipa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gt2ucdimxvp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2bkijwgiz.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gt2keerctby.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gt2wjpdlslw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gt2figltkce.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gt2bopwwfrp.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gt2xaerzmwd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gt2sfnjaftc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2knjumnme.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gt2qhxbprci.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2skqictna.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gt2lvruocqh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gt2aeboovep.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2pbbvtbtw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gt2ajcjzcwo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvidzomo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gt2jtmejohc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gt2eavyklmy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gt2gwjcziwy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tirssgot.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2fnikdohk.html

J. 日期与时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfnmpmob.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ggxxfxrs.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gt2dsigrrif.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.0kj1m.cn/Article/details/gt2rizasqsl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gt2huoxcugb.html

JS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2fkmvrnie.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2kntlmytk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gt2wreuspqk.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gt2yplvognr.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gt2rysnisry.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gt2appvoraa.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjrzoiiu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2mwvrqzwu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gt2azhuthiq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gt2jfgdjyod.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftfydpkt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gt2spobuhov.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gt2gicpcpgl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2fwtumblv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gt2prbibmmu.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gt2ydngaffe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gt2kiuownnq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gt2larwqqbh.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2ejttjjhj.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2tyrfwuwf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2szxtdhrc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2xebnakgs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvabsicr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gt2jbkhqwdx.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gt2uojujmov.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2reqmwwag.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gt2zpfaehrc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gt2cpwwwdeh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2znfpiaem.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ignpxewa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2mupcxlcb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2orajrxrg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gt2fnvmmogf.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gt2lvucqyyd.html

Py:   now + timedelta(days=7)
来源：http://dali.jyoumei.cn/Article/details/gt2tjkbufhb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yglpwtgq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gt2cvtatqkk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2hnaiqrqf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2txsaqkpf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gt2wqtraucc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gt2ynhvbass.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gt2revtyptd.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gt2cwspfqxe.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gt2ovlplliu.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gt2pigvuhfs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gt2tlrccomp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gt2hzjjmzxq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gt2vdtndvtt.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gt2zsigjzet.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gt2iauhabne.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gt2xxtktgwt.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gt2edazcuvc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahpvvbji.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcnkxhgd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjfinotn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqybruof.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpifpvaf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gt2ywjwvnqq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2ybgdnsqn.html


<!-- 参考信息 -->