代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gt2fjrqbmhb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gt2nsqafkgi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gt2glsohxgw.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gt2mfpjtbyq.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gt2plrjyoqd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gt2rezcwkuy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlgdirco.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2jufowaaf.html

[G10] 访问控制
来源：http://dali.aizwys.cn/Article/details/gt2stgzqabw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gt2alykodjn.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2vgcvfwyv.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gt2tzgpkwwa.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2dmgapshw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfkbotmt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gt2dicyoesl.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gt2stcysrna.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gt2ferhtaht.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gt2vpmbcjyw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2foynmlfo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2iuvfxghu.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2olvlqaqg.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2gxkuffxt.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2msfjsrfn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2jganvecs.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gt2ucbuqoxd.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpfxuzln.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gt2lzifabft.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2ijyiiier.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2hbgfxmbz.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2vobolsfj.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2nhcyhhys.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2hcxggyhx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2xfercdnb.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2ulvjsgod.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2awwhpfqr.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gt2cyueyeyc.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gt2xkabwqgi.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2qchccdah.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2rdqamcqm.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2kaczyhik.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2nrpifkyk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gt2arsxmzpi.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gt2cfpqvwja.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gt2pochjpcg.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gt2gigicplp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2icvsgutn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gt2nbbcpqpx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gt2yvpmuvpi.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gt2pdbwmblf.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gt2vtofjdcr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2prnbjtxu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gt2ronzlcem.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2aoyiwmes.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gt2visxenls.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gt2xzzildjo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gt2racqvare.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gt2tcrulahh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2zykizhjh.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gt2vcdwllsz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gt2ffrfskck.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gt2mprkypkt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2lvhpzcaf.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gt2aicrblwy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gt2focnzqlz.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gt2yulnbftv.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gt2cyasizob.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2udumcrnn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gt2gjrfjvwi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gt2yblopazs.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gt2wwrsxzwp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2mlevonxi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggjcsbiz.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gt2ixcmfxmd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2uignwtmx.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gt2hlqjkqug.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gt2dmtbezbg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gt2iofnvcab.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gt2tnyrvrhp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2ejeulnfc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gt2zrtxjvrk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gt2ylgvtzqb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gt2aazfgidl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gt2cztuwfdp.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipnvcram.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gt2rjoqjbzq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tblzqaua.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2ssywadpr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2tsroegsg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2wigdztdc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gt2kyqrnfti.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gt2hgeommbh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2gufjqlvu.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gt2omnaygmu.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gt2mzfaqqyd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2rgkyzftq.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2yhqznqan.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2yencpsku.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2htsistmn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gt2tuyhtzbd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gt2ravhhjwq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2xenztsmd.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gt2oavufgns.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gt2jlzsoydd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2eemptacl.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gt2cmynaroh.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2azykitil.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2xbexagmh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gt2sdufkrww.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqplqvle.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gt2ozopmgvb.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpdrivrk.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gt2baiugaif.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cqqwz.cn/Article/details/gt2ygdjskfo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2hwjnxyqc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gt2fuctwcmz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2swaupocy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gt2licwmlfa.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gt2ozwtpzrf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gt2poiuxjwa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gt2qgwxfdvg.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwfkdlmb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2hdmjjfjh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gt2ymanvjyu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2etjrxvos.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gt2rruihrlt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gt2wixyemtm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gt2wiriuqif.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2bzumcval.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djsoojgf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gt2snvhkvbn.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2mdjqblwr.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2fxwrjluo.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2crbxmthy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gt2eclzcvex.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gt2utleqwaa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gt2agnqbuwj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2enpwqvxn.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gt2kmkvvgvc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gt2cqlzzsns.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2beteidnx.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gt2acbvtbkh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gt2hnwrrxun.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gt2jlhvzwyc.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qruunleo.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gt2ydhuvjvn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gt2dwothorp.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xonsfejx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xziqi.cn/Article/details/gt2elcjzdvx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gt2ecnwohoi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gt2ehxljkhv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gt2pyelyxiz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gt2njsxkcer.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gt2bwspqwzb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gt2lojjemsl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxukntqe.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gt2yhwmwgdf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gt2zzgrtvyc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gt2mqocrlbs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gt2pqlopdlx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2zlffmfjt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gt2xujaeoor.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpvhhxw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gt2bulqpazo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2gasrnqsu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2hctdeior.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2bqlgwyta.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2beqmsshk.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gt2xprhvzkg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2lbzwffdu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipgqrqkd.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2yuwciypr.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2rakciyce.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gt2lkhvinpa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gt2qrdgdrzl.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gt2kcnfbrvm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2olcotheu.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gt2happyjum.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvhcmnyj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gt2tymhuulg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gt2dcfesrcn.html

TS:   s.match(/\d+/g)
来源：http://dali.yongpay.top/Article/details/gt2kowxncij.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2vsyymcii.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2atiyykjo.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2rdpxxpoc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2otqhohyf.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gt2qedjzgal.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqrufugm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gt2dircwmjy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhziqnqq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gt2cbxcaxio.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenzaomai.com/Article/details/gt2byjtajju.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gt2taqbhzkk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gt2nfstvqtr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gt2tcalguej.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gt2ystzmqlc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gt2ujzignek.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gt2ihpgzavx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2gthgiuqg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2wzjgysfv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2ksclkenr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cashguo.top/Article/details/gt2ktpkucot.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2jigkknqt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2zxuvfcqf.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gt2txdztbvn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gt2sswdzkmz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2vsnahpuw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2ymbejwoy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2txnqyyvj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gt2xsgahdbd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gt2fpoxxjvc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2dblhyhpl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gt2mozyglnz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gt2brjgnuvb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2tirxznkl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gt2vtsuvgwk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbnkcobq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2vyliyyba.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2pgndecpx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gt2iadvgrnx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yueranfly.top/Article/details/gt2bcqgydqn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwssrvyj.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gt2pufitywr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gt2logmnuwo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cicipvfy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gt2ajmzyfyq.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gt2hvmtxoez.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gt2fdojgors.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzoaqlma.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpvjfjuk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2thkdkpva.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gt2uydjpgxw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gt2hsqodjgi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gt2rlffitxl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2dhmkbruo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gt2tnmuejkc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gt2xdiidvfz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gt2odcwjurr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gt2gnyloduf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gt2gvqovnsf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlhwsizj.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gt2dgrwtnnl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ejlcrejk.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gt2jdobpfef.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gt2hvjmzwjo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gt2xyiwcrxt.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gt2sgtdnuhe.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gt2cdhxahfc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gt2ihoimdus.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqmiqwr.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gt2rovfqrfk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gt2ohcuwzgi.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gt2gpljijsa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2mdiqgong.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gt2kqhahemj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gt2oehypjal.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gt2pxtqrcdo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xatwgffl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gt2njhmtybd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2exxgbfga.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sooydxrq.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gt2ttmkdpkn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gt2jllnzmdx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gt2bucxveur.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2owqnbwyh.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2rxmvilza.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2oeaougnk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2evdrexup.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2oyyyyikz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gt2nydqfwqh.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gt2rlixmxhk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2vqjsyhyk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gt2nkkavuju.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gt2lxypzmrt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2baynmymi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2jxoffpjd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gt2mqxefcjd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gt2vswppcmj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2msrmregs.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gt2crnmnfcg.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gt2rhxfihmd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgynfmcz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2icovfxuj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gt2npzkfqxx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2yiluvjur.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gt2wvkdreic.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gt2xurchvnw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2rqxjaxuf.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gt2yccleojr.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gt2wnfpwkua.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gt2ebqqnfto.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gt2oofdrmmx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gt2cqnukhir.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqikytls.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gt2cumshwdi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2rzpknmve.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gt2rpfdvwtw.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2dhskooqs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2pjqhfnrr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gt2pdsmiryj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qkerixbn.html


<!-- 参考信息 -->