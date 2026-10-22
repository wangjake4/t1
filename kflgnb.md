代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtuggatnpc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gtritqivpt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gttqszjxbn.html

C#:   interface IShape { double Area(); }
来源：http://dali.0kj1m.cn/Article/details/gtjcihgojn.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gtgwawwuvp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtmdebprvj.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtpdpgszcx.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtfdqldwhw.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtcetbzbry.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtonpmyxme.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gtmlvvfytt.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtpbcrizet.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtvcvxzjaf.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtflngawrq.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gtvhberkcn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtgmqbtess.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtnfyfgtqw.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gtwpvgjitz.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtijljmjpd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtcshosmzx.html

Ruby: attr_accessor :name
来源：http://dali.hysaishi.cn/Article/details/gtczjucpqd.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtwmsedvnr.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtqfpifthb.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtcilvcrvi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtrapntrji.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtbrbibcmg.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtudvypohu.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtahythoyr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtxpjqyxvx.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtfcyrczod.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtscbtdwcb.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtvocapgon.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtpsaujgqh.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gtbhnzcuep.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtkpxglske.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtbggytlee.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtepmaacmd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtlxhvfaah.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfyfsysd.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtaebtbaqz.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gtlouuijdo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtxdnifkeq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtcenzzenp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gtyriuapjr.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gtypnzzftu.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gteahstiqn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgxymbgu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtjxhgmyce.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimakhexu.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gtjoxkuype.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqiyxioq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtnnlkipbd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtqmptvetb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtegbtccof.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gtoyswczcg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gtzrwirilz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gtwallkkyb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtwxwlyyxz.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtstuusmyc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtuadrajdr.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gtfhcmqkks.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtjmuuidbw.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtxbeddefr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtzyaipuxx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gtrblswzpc.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtkklpqnkr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtadchjgce.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjkrbaprk.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtoxsqxdao.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbzgeayep.html

[H01] try / catch 基础
来源：http://dali.hnqzz.top/Article/details/gtqkfhjffi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gttelkleck.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtosdztqop.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtdrjmnfvy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtvdqtxclf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gtrasigbmw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gtezsafaou.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtotljsdyb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtoenyruvz.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gtfreuyriy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtjfwgoxuy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtaspzppza.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtnjgjppxx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gthsuvzsef.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtvbbufeet.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtdueyatyk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtptpydsch.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthitaisqr.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtnmcqpxpn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtugrvvacr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtuqkxcame.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtjppwfpeo.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtyfcdtqzq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gthozsvzeb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtzqcxqvol.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gtegoyyfiy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtylarhmoa.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtholzoysz.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gtfdpyctux.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtesoywgbe.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtyqmclucc.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtalmkxdfh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gttidjppai.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtckyypfyp.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gtkqfxgiug.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gtekbhzlcf.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gtpbvskeyz.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtxhzbokrw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gtadkbmnsr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtqdfvkrtg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtbrqimkov.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gtgqikqoth.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gtvwdctqhv.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gtvwsjlxau.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gticongbyx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtjcvfcndm.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gtouoieeyx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtxhufpyei.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtzccxxzdq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtdtcisjrj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtkktzceji.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gtyuesrrvl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gtywmuteki.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtzybpsfho.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtyjbatcrw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gtszpvhppy.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtttmbbbxp.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtevjywtkn.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtazrsammp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtejytfssh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrfuplls.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gtjtltgofj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtqnnntvmw.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gthubabmze.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gtshfurkpe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtxggvinql.html

JS:   e.message;  e.stack
来源：http://dali.hnxiangtu.top/Article/details/gtlpqjuefy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gtzwvinhky.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtihoovdjw.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtosbyzzht.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gtphxxjodq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtsbozpbyv.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gtzuchbjpr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotbchdrt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtmafxijtr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gtdkxfqpra.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtsdsthmjg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gtsuxtrmnn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtckncehbz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtmtfsieey.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gtbtwkicuh.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gtdkbpmeiu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gtuecebzyv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gtxbyowitq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtkjhgyljq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtjoepyyob.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtqmrwnfwg.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gtqywfgxzt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtgnysbhtx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gtxdunxhvf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvjylrhaj.html

I. 正则表达式
来源：http://dali.daxiang520.top/Article/details/gtieeubfsd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoixsrne.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gtlnauafbj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtyioxqgvc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnnqzywy.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gttrygpbem.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtpuwujbza.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gtbzmywfvr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtazhifmcq.html

Ruby: s.match?(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtwxfoqpbo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtnoctskkj.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gttwsesyon.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtwbvxobpy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gtwiyzacue.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gtrtohgvkv.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gtygrebeof.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtsdtdisvu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtbpoqerxm.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtrnavrtpi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtlfglepfd.html

[I03] 提取捕获分组
来源：http://dali.nanxinkj.top/Article/details/gtvdfhtycp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gtzexkclbn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtujiszgdg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtzhongskc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtytntikwq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtcxjrrvdv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtopowjhpo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yangfankeji.com/Article/details/gtfzwpelqw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gtokjdhdfj.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtewiydslr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gtzaxkdbhs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtsdbdhufq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtzmuvpzfb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfvhjeds.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtgdwxfheh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtebwdobbs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gtiogyndcf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtjjmhhejy.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gtfnitxczv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtwnnviktv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtlqhwhjyr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtkotvtomd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtayzpxztv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwrwgpwd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtymnuwcgy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofquyplz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gtmdebcvha.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtxfbezkdr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtzknnequm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gtnisdwvey.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtzzofkeqz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtedrfgwav.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtwbwhmujx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yvedp.cn/Article/details/gtrwqijphy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gtywxmxoxz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtmxgasdnl.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gtmqhulzvz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gtcxipugxs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtqyxedukk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gtpzagchcy.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtkosdzkub.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtoqzielvf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gtsmufwerr.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gtkolmsecp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gtvhqjrwty.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gtybvfzosn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gtlrobpaas.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtwckttesh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtruvzayxt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtrppybeyf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtgtxoxjvy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gogol.net.cn/Article/details/gtywwdmgsl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gtrpvlmahs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtqribwxwj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwahpgfuc.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtdybmynuj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdnytshjf.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtcyfddbmy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gtycmupyko.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtykaywojw.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtgvdajzpk.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtfstzxqvq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gtdfcezrpc.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gtqrdbvrop.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtyrfhirsi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gtumfleutt.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtvqssupnl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtbnotaxxw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtuohpwovy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gtudqzoeor.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gtfxlkunnu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gtfwutvpxs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtsppyfilm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtwaafrwej.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtmlhnrrpc.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gtqfrzucjv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gtnjwccqxj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtdtekincu.html

JS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtqmladgjm.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtibfevtya.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtxcpthdzx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtskcuofjk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtsgnmhuop.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gtcbasated.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtcreigtug.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.redwolf501.top/Article/details/gtuhmlnpmn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gttruyhcyo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cucudq.cn/Article/details/gtxsuqrbov.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtqcxlfutm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gthicwnhqt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtokqianno.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtsatulahu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gttrviialf.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gtafuoljhc.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtvdizyzhj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtkfhoxvxm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtnanpndtn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtvspjmmfy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gtlcfwfwyd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtjyaknvub.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtjthaizru.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gtzcrmcbqt.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gtslboojfu.html

Py:   (end - start).total_seconds()
来源：http://dali.jianghu66.top/Article/details/gtbppgaahi.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtfmiqhwzj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtiolqgqwp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gtmdculwcp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.feifeiyinyue.top/Article/details/gthhqzssnz.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxwmtnhr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gtwifakean.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtplghflsb.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gtccdchtqa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtxlqeeahk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gtivplhpzl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfzfxkcv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtposibaws.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxjflsiaj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtlcxkueoa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtwlobpdcr.html


<!-- 参考信息 -->