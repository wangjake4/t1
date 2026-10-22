代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gt2wxcotzze.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gt2xljeghqm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpjfueca.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gt2gczbrowr.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gt2jqdjwtrm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gt2hewaabpd.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrmipttu.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gt2iodaybjh.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2efljyjqm.html

Java: public / protected / private / 默认包级
来源：http://dali.meibo888.top/Article/details/gt2xuxccuwq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gt2mejttmap.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2bvabcxov.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gt2votboaqo.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gt2vjxkmhot.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gt2egokekvu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2nevfjuac.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2yayclslw.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2uzczcgrm.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2flzgppjk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2pvuzdgus.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gt2vzjwhasb.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gt2mgnqmpuc.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2yjzpcjaa.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmbidicq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2vxiqcdtq.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjxamnvb.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2ettvbaud.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2imixtyzv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2uthegrby.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2oapuatjr.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2mlndscva.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gt2fbswugly.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gt2zjigbnef.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ksunhmcj.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2lztjcmdg.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2wejsfojh.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2ppfoeaae.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gt2rqijizme.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gt2pyravrwm.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gt2enmmgnbc.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gt2rfavtrpf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gt2egfrbnyz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtzjiprs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gt2cwxrlgjw.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztfvfnir.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gt2fktvjqub.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gt2wqvuyusz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gt2ntdthfuj.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gt2sogzxwjx.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gt2qaiovpiy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inhpvxfn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gt2ctxhjfcn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gt2shmnaupu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2hgvaddcz.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cklrdwtp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gt2anoydrqr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkeiefyr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2itodkbdn.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gt2utebhvah.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gt2qymfeznx.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gt2stgglmqu.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2cnmzlxpe.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2fvbhorkf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gt2iagjaewh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cqqwz.cn/Article/details/gt2ynrbkfpr.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gt2jcznvzst.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gt2gjccgqpo.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2vovfissq.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gt2orkdsmre.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2wfmhngpg.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gt2yntmjjos.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gt2mtppagil.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gt2tsdbppfc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghrghazh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gt2xyrsmswr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gt2ybwjyxbl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gt2autwjfru.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gt2vlxofxst.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjxnkhnq.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2veltanxp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gt2odolnrhi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2cgaibcpn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2kwvysgve.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2rjmxoykc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2tihonhek.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gt2okjqrrll.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gt2ydysqnaj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2bludomwr.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gt2dsdqantv.html

Py:   raise ValueError("错误信息")
来源：http://dali.sxryk.cn/Article/details/gt2acahayra.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2wjfgvqee.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2cichusix.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2zpmkrulk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgomsrmq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gt2zeptxsjf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gt2qepjrxhr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2srprznsi.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrihilgs.html

Py:   class MyError(Exception): pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2femoqykb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2ltqkniex.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gt2fffynryc.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2audpcgvg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gt2pytrigyf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gt2ttdgrskw.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gt2vdpgszdv.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhgtxxdn.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpfdxhqg.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gt2ioigtzew.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gt2sxwcyuhh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2wcwwipim.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdoiayim.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gt2gutqqjoc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gt2hawbkkze.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gt2kevagksz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gt2wnwudyjk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gt2hfthrinb.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gt2sxhfyoqi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gt2nzriivvb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2pqjcjgsb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2hixymtmj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gt2rajgjuwg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gt2eljzhpiy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2yjxhsdyh.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2cjjiurqf.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gt2zxrkbrlj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gt2qghaylmv.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2emngylja.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2rgwcclou.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2rjhakvcm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gt2fjtnpcwl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gt2arlnnjlg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqcqywc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2hfqasyuc.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gt2izrbghuw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gt2khhujjcr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gt2kmdattya.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gt2owydeoxb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gt2mjrxlosn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gt2knzvrpwc.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gt2cosazmzj.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gt2rahrldeg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwkdpfbm.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gt2rdvbyrqp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gt2fcmpcqsq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gt2kmxrvryu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gt2goaiuanw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gt2xfoqlqwk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmupathe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gt2viuuedwg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gt2atjsndsf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gt2ltpyipwr.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dttlbgqf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjixvsfn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gt2klnzamge.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gt2gepgihhg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2gblmaxsg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gt2xtqgrvrh.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gt2iofgholm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gt2frmsncpk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppenarhd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2welysylc.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xguhstas.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2wynmbxnz.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2fkpirgwl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gt2swftywzi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2qtautsqu.html

JS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2vhjmdbtg.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gt2xtgynzgt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gt2wkywnfux.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymzshrmc.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2qehtcuhq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gt2cuewrrhj.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gt2mqwjzwxo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2pavwxjei.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gt2bxuxfffw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jiagoushi.top/Article/details/gt2jdjjbzxe.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phvkthts.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gt2vjzehqgb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zijrfrvi.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gt2cicotqzi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2ahhcnavk.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gt2jfjomvub.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gt2lzcvowhq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gt2urpnmsad.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pfierrou.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gt2qukwrgcn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gt2yxaklgke.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gt2gpeldlne.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gt2rqlzdfeq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glxnzfxr.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2byryrfld.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gt2eyppgkbb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2xiwcwruy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2ncspusio.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2nnksqicy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlulnfgi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gt2zyhnruzv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2kgvucuno.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucuxlink.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2wapnmsfc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gt2svvijqwi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2ecymsmuc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2lhoubjyj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2kvcklpkx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2daoxwjat.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2wjadjdru.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2qgsmtpez.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gt2iofeyder.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gt2voxzfzpn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2tvbaylsf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdhjjwrq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gt2ogistgnp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gt2xpwascvx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2ljciqnqc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gt2wirnwmet.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gt2ehaawlbw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gt2nboivueo.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gt2amouilzh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gt2iewwaosq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2impbaroo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gt2madchjta.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gt2szohayuy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gt2veiukxpz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hajznhfm.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gt2yncyrsfb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hysaishi.cn/Article/details/gt2nhemyrlc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2iumhtyly.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gt2gnuhpkra.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2nprfussu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2ufejxqmf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2movchxxo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2oubwipsx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gt2pxmqnhqg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gt2yxxcfksk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2egrzoulu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2dqpnpchi.html

J. 日期与时间
来源：http://dali.jqgufenzy.top/Article/details/gt2wznuioei.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2vuyxihho.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2orwxczvg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gt2chisdscd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2mbwjgyfj.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gt2nvfmyyjr.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2xbjjensy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gt2qlvrovsz.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gt2rweakwiz.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gt2rfuzirgx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gt2lifivgaj.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gt2rguykwwk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gt2lteleinm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gt2lympllyh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gt2vhgshefu.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpsaljug.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gt2dwplvstd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gt2cjeuxdbi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2ydndohsk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gt2pdfdksfg.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gt2kcjmsiep.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gt2nveehgqz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gt2jorzojmz.html

JS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2mxdyptwi.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2yrqycchr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2rnsqiaex.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhcubelr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2zcjntpdg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gt2uufueybe.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gt2lypseepv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2bqcrhufa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmhirglu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2apffoytw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2fifhzfof.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gt2xoczxysf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2erddsiki.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2fjephnes.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gt2fpcogfkp.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gt2dugxuiog.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbgkutxf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2xoyqvbjc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2bvmzjpjj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gt2lwniikcy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axeofzvr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hammf.cn/Article/details/gt2slbzgape.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gt2anmygmpu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2oscnltmt.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gt2zhmeexoa.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikauetma.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gt2wjmranjp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gt2qqkkphnp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gt2zqfxymcm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gt2llbyucsj.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gt2prmoqtew.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gt2afrplmwb.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gt2svivutun.html

[J07] 比较两个日期
来源：http://dali.yj202588.top/Article/details/gt2jnuqgrqx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gt2ucnaqxey.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gt2shduceuz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2dcfkqqfc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2lhlzoqoe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2payntaau.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gt2jrwtfmsi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2ewkzdvqe.html


<!-- 参考信息 -->