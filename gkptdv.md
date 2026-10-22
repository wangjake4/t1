代发 wailian999

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtyaswcikk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtfhntrgjz.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gtsfxrqdkg.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gtquqjkvdd.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtyqygtftq.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gtngrwyznw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtyriaqlvr.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtndtxnypx.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gtehikeqps.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtqaqjcayo.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gthzhuaflp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqnygoymh.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtzlismruo.html

TS:   get name(): string { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtpqalzmtg.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtdtkxyyzh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtgvvoyanw.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtnoepmpas.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtcayakgmf.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtxmpkflzr.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtbwciahqt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtuebzpgkb.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtgjtmkmzy.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtexleqbop.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtepiewuuh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gthyihgknr.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gtshgzvkzv.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gtklbvqgpe.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gtfpvnreba.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gtxoycknew.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtwafxgdnk.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtdpuvkixr.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtqairnndp.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtpgqtgqhp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtnmrcjtyz.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gtgxmrfcde.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gtkbkfikmu.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gtllbseiwp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtpinghhcu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cqqwz.cn/Article/details/gtoblbnmfc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtahqqhfbe.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gthqwxrlsm.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gtcxhwhnhu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtwohnfkuq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gteqgarusp.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtocaxbddv.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtftfergns.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gtxzjihejc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtjbjaqvhd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtkpxljgph.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtgirpxyjg.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtexxqhfsz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtyqehazcf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtwuqyenzh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtcgbirmok.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtgrjlmaks.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gtksusheaz.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtcitxlgdd.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gticeprmwv.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtitzgmqtr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtshmisrsi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtirkbabkv.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtuozlcpjd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gttcdxtxuf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijwedjag.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gteuyvvgkk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfkoazpfz.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtajdtcrbv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtjbebrdhq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtfjqwcmva.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtlbovdicq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtqevyahnq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gtnmcfqmpf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtliuuxcrd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtynzjphqz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gthtcmpsgf.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gthavxixbl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtijlilcxf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gttxddyjxm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtqzygxbkq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtztteoyes.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gttgzbgjoq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gtwvnxkrpb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gtumvvvfoi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtwbilsadx.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtkhxgghkc.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtigdxomuz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtiokgnpsk.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtuqvwfgvw.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtjtwfnvje.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtonzjxnqg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gtkndhyuvk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtenbfyfud.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtzudjrnna.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gtblowqjpl.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gticvkbtup.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtkivobkbd.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtqfugjfdj.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtqktzoeqc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtcbhivfmz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gtfasojfqs.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtuzhonpis.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtmmwfvlve.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpifmjox.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhvmyymb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gtpvptfdpm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtetcbpvpl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gthmhawvek.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gtnyouuipf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gttuxjbqbw.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtuzfvjysq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gtmxwforqc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gtsmvvquhe.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gttedfjori.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtgobggmty.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gthmavhdmk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gthgspwthx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gaohongyu789.top/Article/details/gtuqpyunub.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gthzmubcnt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtuvlisxop.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gtfysrbspc.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtbxeeajjc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gthxthgtty.html

PHP:  assert($x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtvovksuku.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtinkelkkt.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtdmasuakb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtrdblimft.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtokkmzsqf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tanke756.top/Article/details/gttcnkjdpg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtwadbgycn.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gtduhakles.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtvulycmua.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtoigajrck.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gtrkhqoxrf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtszbyzhog.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtyaeqcwir.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtvbelsliv.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gtrkfeicdz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gtbearpizs.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtygywmsxm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnxiangtu.top/Article/details/gtiqocoyfq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gtzllyxkjh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gtrhsmfldx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gthllvxoos.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtqqziexjp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gtadlfhwbu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtmthjiicy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljiayvyj.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gtnrnbvake.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gttxrlupxf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtgqnmyere.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtecncthym.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtuznnlgyc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gtgfytqzbw.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gtchmidvuk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gtgtkcvoxd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtzdxhxstt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvdsozyaw.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtwrhctynd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtveyegqtq.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gtjaphyxoq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtcyztidhw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gthekxeivs.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtnkakmsku.html

TS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtpprfsrok.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gtwodzeyli.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cashguo.top/Article/details/gtzjiggotk.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtwjpugvrj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gteguirsig.html

[I02] 提取所有匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtxagtrn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtduvlpsbx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtcdjqsjiz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtaflzsvwc.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtiktvplfd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtcflmjddg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gttfzwnqvl.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtcsnkuktv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtrqfekdkm.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gtiotltren.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtrozpzzdb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtbnedirxx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtrestlojd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gtqcoyyzye.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gtrteettjm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gtcwmggkhk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gtnwzeiafm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gtjcjhkwak.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gtqlcsuzkh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgesonggn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtbmkihokz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtdamvgjtj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvacptpe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtbiakjbws.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtzdrrcknh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtqzdirbdk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtahxhnueq.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gtfdlsjcfr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gtrygukmoi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gtyaaqruef.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtrdapvjlo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtujgdartb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gtsrjzmspe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtdvlltkkr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtkkneizyz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gtooslsass.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtyjyddrvc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gthzcesvbh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gtfszjbdkd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrrwjabm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtawgruuah.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtorgoryls.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtqghvifxm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gttvcxawtv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtxsbyhejq.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtldtruzem.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtsrnrknmm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtzftvqyeu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gtxcejwbsd.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gtuehqqqmx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtjupipwnp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gtewozynyp.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gtsgezrnvs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gtgmqggqjq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gtmjclbymk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gotoacloud.top/Article/details/gtmcpobqat.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtihhhtulw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtafnmvipg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtexouwolj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtodxqoxce.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gtyqevodtk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtgelvdqrj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtkqhyhtyf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtiutdvrph.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gttrgfcnkf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtczigeald.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawqkjtva.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jlsjyb.cn/Article/details/gthhnthcto.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtuzpfited.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtexpptpdf.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtmdedlzoj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gtqvbaryxo.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gttpdozvbh.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gtetijmhjo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtvbduiaqp.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtnziupdwx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gttcvvkfyy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtydzmqvkr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtyrkbngpj.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gtnevjlzpd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gtvtflkvii.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gtsxpbchyj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtnzbvknns.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gthbiwdjal.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtxwdptwxz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dashuyun.cn/Article/details/gtwqhqldww.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtzciglbdy.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtmbsbself.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtigdoaafx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtrkeukg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtyuuirlcg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtesbvosel.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gtvdlirymf.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gtjpgvehuq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gtrqnfpcgm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxdykpkx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtolrkhpao.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gtvstrmcvu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gtzukpvytp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtohcunlwr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gthowwozfg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtnibvipzy.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gthplllaaw.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gtzrpnypqo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gteafupwoz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmpzwyym.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtxnglmxxo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gtetwxhxzs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gtoxtvmnjw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gtjpgjcbkp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtxblovrdm.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gtfavxatup.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gttynldhfi.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtbhxpvqpx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gteqaosnce.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gtwfvtbskv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcasabut.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gtguftprmr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gtosxwlore.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegbkctan.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gtlcslaekd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtqoarlsdp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gtavovmhuf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtkfomnsjz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtnzyhtdxv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gtpltmcsjg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxncuazf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtilwfiybc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtgninadcw.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gthmgzjtfq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gtgepsliib.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrzovwol.html


<!-- 参考信息 -->