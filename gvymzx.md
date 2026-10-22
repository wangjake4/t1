代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtpejjelzu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtjscjxxtg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtzytmyrnj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gtqkmoenmc.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtpginhgpw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtmbvmfehc.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtrksvhpln.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtwlfunxff.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtynoqgcrn.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gtxlivmkmq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gtkcamktke.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtlbrggyur.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyehalowg.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtfupgkwmy.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtivrpfcun.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gttnfmrfdy.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtlwphijgm.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtezteylnm.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtlsaaxmor.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtgjbhsrxg.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gtccfikpba.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gttdvhmsrc.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtrrxsjusc.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtinrvppni.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtroyxuwbu.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtmxdrbewd.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcecfeib.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtbxzlpati.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtpufxwdrd.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gttqxgorni.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gtmziflxvs.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gtbpmkxtvj.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtbmcsqtee.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtuiikbkjd.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtoieztiil.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtajmnufmy.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gttkepycex.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gtbqhuuugc.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gttbemfkcn.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtpiswfija.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtifmsteuc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gtlyfsmolp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gtvugbklvo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtinevmhpq.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtbhrksazv.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtuaheyulx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtqxfmrfop.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gtbdtbisva.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gtsuwqvogf.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gtvgcdeezb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtphmfwquy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gtwukwdoxc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gtasnnygjo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtevhmmfwm.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtnvzxbpiy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtgpnwlckx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gtwkslzjvx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtnfeitryk.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtetykliwn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gtrgzglvpu.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gthqxiduni.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtfibeqvtd.html

TS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtgzkhebnw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtaroeokml.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gtvvqwqinc.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gtivmxddhs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtorklvbqz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfrntakhs.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtlmhzxfwl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttbcpbosu.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gtdzmqeyle.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtxuvmdlqf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtnjvbhcjv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtjokmcomq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtkjmyktmj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gtxqjmhwsw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gthxndrkym.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gtmzvgbhcr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gtzaokunho.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaarykhx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gtgbvleglr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtzyppvimz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtqozbyziw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtrhbotzht.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtzhfabinz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtufxkkmhc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gtfbifqvxr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtpfdsqtvf.html

[H03] 主动抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykodcgxf.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtfvfzkdca.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtszybescq.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtlhcozkpw.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtowwaasnn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtgaeyndtt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gtdzcscugz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtvluwpunu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtyccfldsj.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtjvxxvnca.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gthsazgxve.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtkqkltnfs.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gthjatvjjj.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtefactqae.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtfrjliize.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gtltncykis.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtfjjsreeu.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtcieerepo.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtsyqhmvdn.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gtpbsuwumo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtjmefiskq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtfnyjxckb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtrnxdaxcm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtznfakvym.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gtmjytvtmc.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtwkdgywxq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gtgiiibpnp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gtcjkjgupm.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gtcwzkdnim.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtwbmlxfbb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gthsqrjlli.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtcptvmrwy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtilgrmtis.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gtkededudy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gttwxowksa.html

C#:   obj?.A?.B ?? default
来源：http://dali.ivvv.top/Article/details/gtcsjsmxgq.html

[H07] 断言
来源：http://dali.yueranfly.top/Article/details/gteyfnibae.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gtkaqpuvox.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtqycssehr.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtdesjasbb.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtleowtxmm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gtsdepfizg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtswotfkir.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtwlgzwbbr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtpznnocjn.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gtddadytbz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtgzplafwz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gtwseiyvot.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gtlgpdkvix.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gtklrcljyr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gthhjrbjxd.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtmkorqatr.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gttegtwypk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gtdbhwfphf.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtqbtjkmmq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gthosywvzg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtkzbzluwd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gtnccwqcap.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtywikchic.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtdavrhyov.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtgrvpaszx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtpcxwwtnx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gtrjjliodp.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtaskpzojn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtyzsyztjp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gtmyhjerqb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtkvrxtgji.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkrcbvga.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gtazrdgljg.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gtmuxwwxkg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtvufnmzbo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfkkxpdr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtylarlbol.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtxeeivpvq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgduoxcpk.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjedgeekm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtlwpovzng.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtemotspry.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtctdulcro.html

TS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtonsrfrfk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gtzounphbd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtsodxzavm.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtxmhxwgoe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtesvyiffk.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gtxcehsymz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtxgvnelpv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gtkyoyisvf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gttxvmpnnr.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gttmspfmib.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gtdhuhnpix.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gthjbblhxh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueacyaim.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtxxttnrgq.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gtlvkotijt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gtfmvvkvvc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gtglnnxcpm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtfmdomggp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gtndheizwe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zdqjudy.top/Article/details/gtxwtjdacd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gtdqvqkjwi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtcsgekpmf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtrznohzon.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gtgxdkwrdm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgyzjwin.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gtxfriqlak.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtsmndzijl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtneskkxae.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtibbivtlt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gtoytkyriz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gtzusncqhw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtrukivakg.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gtqffdhksw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gtrxfoqruu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtjdymynjt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtiesfvzme.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtbxzespjb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gtxusepojy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkpldkry.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtztccqkbs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gtyvqoidfm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtmykusfjw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtoolvmvtd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncmjeewf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtecpimyrn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gthnnmmnwe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gthfowoyaj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gturntfbhb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gtyyczczbx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtzqusfzlg.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gtpdtqngqg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtntxxfunl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtjfvtajaz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gtchmfvblv.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gtqgegejij.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtyfiqdznd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gteqkszoya.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtclfiioiu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gtbidpvppu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtqjgrswlw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtufaqhtnn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtddqayqhs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtbncnprwm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtjjwmhhyi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtciogfpjh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gtebnkjbsp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gtgtzdywox.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtnsyxdoax.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtuoobqxpd.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtaurqmlmh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnktaoad.html

[J01] 获取当前时间
来源：http://dali.xylfe.cn/Article/details/gtermsvncb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gtcphchyeh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtmshohkft.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gthfrdhppj.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtfyjrbpfp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gtchudefty.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtslmxluyp.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtknynxdrs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gtjwsphfxo.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtqqocxkwn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtkwjopbfs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtctynpcnd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gtwhmncmid.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gtvifqojdr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gtiruznrtc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gtieoirbwu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtwvidoubz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gtnluzbrgn.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gtorvsufbf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtunhzhjvk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gtqabwgfwg.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtndsuewsz.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtzxprglkw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtpmvehend.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtesosezgy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtmlxbreoh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtxawuijhs.html

[J04] 时间戳与日期互转
来源：http://dali.nanxinkj.top/Article/details/gtxkfrogib.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtzzssjkjc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gtpoylwppt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtqegcjjwx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gtbhlaoceq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnlwyhif.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtvwlbcetb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtgjszqkpe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtbbbhurja.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtnghvvfhe.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gtfneqatdh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gtmayffobv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtmrkzcqad.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtizczafuw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqakpypqv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gttkdjvrua.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gtuynbtjlt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtbctbhykc.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gtcjkiyqjx.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gtjvdcasvp.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtrukrajfw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtyqichjyj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gtuahrpyhm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gtdtrsmqyj.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrsmwjos.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtwbkgjsvg.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gtbvcngsxz.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gtlfjloqfk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtvgswpqnw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtlvgbzmae.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtcixkfenk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtiusdhdgn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gtczxibsho.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gtogxrccnb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtuzlcgdsb.html


<!-- 参考信息 -->