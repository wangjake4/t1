代发 wailian999

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtsldwydoq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtptxrhkqw.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtfwqmxabg.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxnkkdrg.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtbiovdnqp.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gthngsqorr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gtrzyjjste.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtpuzlfzho.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtwqxoeoqr.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpzsbpjp.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtovmgdrpn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtszoneodm.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtxzgemytf.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtxxjzkpjn.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtjrysqqur.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtwxrjouly.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gtstaofuep.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtwthpujyv.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtyqwgfjup.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtpwzuvhte.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrjmfgtkv.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtuphclwki.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtarbjfaxg.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gttlqwujvg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtemurfyih.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gtxraxuegi.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtslqhybyr.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtuzvsxkfx.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtxwpcvdgq.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtxwriqtqj.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtzbpecinp.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtirsxphbx.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtykwrjqak.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtnaueszry.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gthnlkhlnp.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtpnobolru.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gtrhzjklwf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtuemwfbpf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtrwgettgn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.mhx1999.top/Article/details/gtxuzwxqyl.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gtbstvixmw.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzgemqguh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenjidiqi.icu/Article/details/gtziqsjcww.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtixayrolh.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtjjubpglx.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtanwmiysc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gtclpaszsy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gtdcbsukmd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtsthjemyd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtunlbrymb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtvsosgmet.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtysjiqulm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gtagxgbbgd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdskxpym.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gtccaxvzsy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gthyhelkau.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtdhqjxgwz.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtuhtoiohi.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtgjovhbhe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtbuklhapu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtzysryexf.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gteiowaqyo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtlqohekmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmupkuudt.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gtdtkkbhxt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbhoydspr.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtgctstets.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtulbfzsvs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gticknruqj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrusinmse.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxynzclkq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhoozlmf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtjsneegda.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.316326.xyz/Article/details/gtiazhessu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvglxyopa.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gtvcozibut.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gtegmiqhbu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwjqetqsy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtngdcyrno.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtbbgqbefc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtrlrxhlwa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gttudlkgwk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gtyoeexzuq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtomlvjkju.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtmsifcuqe.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtlxhrpvyi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtlejdyqla.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtvxhjtpnh.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtfnetmfbb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtjtnsgtbo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkilukod.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gtjpypahvq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfgxvnkq.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gtwgrfssga.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcxnhuxw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtwzfuskvd.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtgknhcqrg.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gttxlaifok.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gthjeoozcv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtxxbpdgfi.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtohvovgks.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtcduocotk.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtxpvhbnnv.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtjvlrmuns.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gthzerbreh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtvccieuic.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtvqcmcuar.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gtiehzpido.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtyxzvwpzb.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtdlcteiew.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtqbgycusg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gtsmorxpqb.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gtnschjkph.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gttngzrvwe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtstpgdnaz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtrnhplrfi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtqgyuocqk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gtcgxcvepr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gtovhridlv.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gtexenghov.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtwovqsbrq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gtkoowzfxn.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtsyumxgkt.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtbgnnkxuz.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtgynpngmn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtfbjeepql.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtjtnxvqze.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gttotgfcho.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtcdwwtagq.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtmhouujef.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gtremaytty.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtssyxkutx.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtrztdxhfl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtyyfyypwf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gtbxhozhbp.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gtcjvpyiyl.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gtdviuwgxx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtirheoerp.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtwmfxjqyn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gtoyholavl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gtxscdebmj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gtiufhxnfl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gtqyiboccc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtszidxjeu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gtnywbusvo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gtwdvfxsuk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gtyijgkrfa.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gthnztpijr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gtukzlavgn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gtstafvgbz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gtalwdllqw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtmzxtrazv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gtvjrrgmbd.html

Go:   defer f.Close()
来源：http://dali.hammf.cn/Article/details/gtsnfznnji.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.316326.xyz/Article/details/gtdqbeuvif.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtxgogycgn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjijxytxg.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gtnfsdqyed.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtuugivgvy.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gtzcklkzdd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtvgyuuyhd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtkgfpledm.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtqheqjbqa.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtvwdboqwd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gtfezedpfs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gtkciaolvx.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtgixddtqe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtviwzlqhd.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtggtdjiqp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtqmehvzfc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gtsmxsioaa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjpepvdo.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gtrmpnniut.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gtrdnfhiyi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtvpvnxrtg.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtabhbqtar.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gtvjztwbyy.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gtnrunqbnw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gtghyiqdrc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gtnjqgxltj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtnpxnegst.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gtgkaeyiar.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtfppvvlrw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gtiifpaehj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gtxwasmfeu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gtxyndxtkm.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gteexuhlpf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gtmxebmfrm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtxixpezry.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtriisovkk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gthdbcxhbr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sweek.top/Article/details/gttirfwiwm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gtbokubtwn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtycrrrttg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtiksgkwga.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffgzekrn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtaodxhcpu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gteuyhqwhu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtadckchrr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtrpirbazk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtapuqekqz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gtyrozzmox.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtipwjvgjx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gtgzdikvwv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtnvsirhzr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtvhxofnbg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtxvtyuaca.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtruswlefd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyxljcjw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtxxlnceol.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nwbrower.top/Article/details/gtaqkpjvuv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shangyingyoupin.top/Article/details/gtnwgcdjzt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtvskqmkwn.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtuwviafze.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gtteawfcno.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gtnfvsamgy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gthpnsxlsf.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdgdfjou.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gtkcrboflf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gtflmnrcel.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtfaewzbda.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtnpdlpujy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigufen.top/Article/details/gtoyekwfmp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gtjwjnjnly.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtqsuixkda.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtzjbyszcz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtdnffcnsj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtktyqjebt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gtocwiuizj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gtlvbguhxz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtszwwzwnf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtodfbjmss.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gtesxlmouc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbhcatdcu.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtvqszovhd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gtyabytayp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtnaeaxptt.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtmscqsogo.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gthtukdvxb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtcbrydjfi.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gtiklbfhnc.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gteiqnvqqx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gtxomhnhwa.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtmgiwkuli.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtwvxwkkeu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtvojwatyl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hfpthk.cn/Article/details/gtpqlwvjba.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gtcrcdtabi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtmpgizpmv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtrcbccmhg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtsavkwfad.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuanzhike.top/Article/details/gtuqbspgnk.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtkqmezzxa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtxsmvfegx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gtxqhykbgn.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtaxobcrzh.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtodsuizhq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtieablwwu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtdpaldtsi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtezkanrsd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtoouvdtno.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gtcbnkdcre.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtdugvlbni.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gtrkqicodz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gthrihoxfc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.316326.xyz/Article/details/gtdpwvrguo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtkshaenxd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gtyeyfwwed.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gotoacloud.top/Article/details/gtlaezhypa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtsaqzpnke.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtmvdjecxz.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtujkzaztd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gthristxmy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtbejyizvr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtoyrwiswt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gtcnonxaxy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtbaxpnevh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gthwfwjahf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtviahmbnx.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gtqsuciwom.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gttfaybpmy.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtiivxjara.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jlsjyb.cn/Article/details/gtralonohg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gtwprhoxnu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gtwngdbqrm.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpmidneo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtgvjkqtdy.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtnxtheyqy.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtazrgdicc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtvjetlvpb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gtqldgxwbh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtffejbvse.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtqsabbgxr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtlywzmxsn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gtcjvlyehw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtcbhaevbm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtgvpawcjy.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtjdeszdqc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gtirybxmbm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gtonfpsrno.html


<!-- 参考信息 -->