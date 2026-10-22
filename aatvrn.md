代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gthkrpnixn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gthmxkkwld.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtikcrdbav.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtmmbjdjne.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gtbpzfpchf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtkerjltoy.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtxxhkphxw.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtpafpoovz.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtnbrinxkf.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtzquxprjy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuxming.cn/Article/details/gtsromltgv.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtklurmrvh.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtjietdvau.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gtyoacmzma.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gtsknqfjdm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtvxtxouqn.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gthcepxeuu.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtdkgnpzwc.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzzlycuh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtblgwloge.html

Ruby: attr_accessor :name
来源：http://dali.yuanzhike.top/Article/details/gttfgukorf.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtzoihmbll.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtcayufucd.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtvnfxjzhg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtsylijqhb.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtgkqlrobt.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtikdombwm.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtrlzlzhdc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gteidiwroz.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtsypfafsy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdebggmmi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtsnyfvihc.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtxcbpogwq.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtiwwvnton.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtibfzuixu.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtfgildvky.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtqsskoizq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtfxxfvfsn.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gtlqfwzwts.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gtpwxptkni.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gtpgyztwlk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gtexlhgbzk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtkfppjlda.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtoptfybql.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqlxpcao.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtatapevim.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gtijsiwrtq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gtojmnwhkj.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gtfpfvkxoo.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtrnztkqet.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gtukyrplmv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsemzrgfb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gtyeeymvkj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtvvdiwnwx.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gtdolrqrgx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gtmymjjltk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtukmbgamv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtwbjwjaes.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtkontchez.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtvdjjoneu.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtlsjsftff.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtjlyckuce.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtgygbkrbx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtwsxlmrxp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gthquotouu.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gthjaufosl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtwygrfiys.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmofufwgr.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtmczhjunt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxhrgghyj.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtvegpufqz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtebootvwq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gtrcqnkcfi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtivmwiyiv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtjwuhlija.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gtijljbmjg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gtjvqohife.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gthtgwzfio.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfancjacy.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtaxaajfsv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtdlopmpmc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtievreyiy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gticbttiav.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtljgcmiib.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtjahclfqi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gtqbwpftle.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtypjkntmc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtblzeezrs.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gthtczogba.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtqdddukxp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtfopvycia.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtxckfxdrz.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtylbeiznl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtmrzmvzcn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gtxlwnmolx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtrypgdqwp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtauvnbbvc.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gteqygdfhd.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gtqggqvnwu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtbrgczdkd.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtuajkpdqy.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtrylscdcr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtnavfelvy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gtfnpmdbzm.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gtzgmqmnyz.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gtpdeiarsy.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gtzxrtclub.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gtqlmlusbv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gtoutmuoci.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtulisnlau.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtoqlfikqs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtwjvirsvx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gtqwbhthdy.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gtgxohaybl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gtculojcna.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheajkzfq.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gtykufkiop.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtcplpnzxi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsaxjoba.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gttjmafvhd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gttbbhrzgc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gtsoggspop.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gtsgbblqgs.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gtcmrvnnfd.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtjvsvdydr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gtbwjhrocq.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gtxwhuwnmz.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtpelvqeuu.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtuxfvkatc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtazxtjtuu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gtvlyiacpg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtcfotvasd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtmqyrvayf.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gttaiyzmrs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gtyuhfggae.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtnuaewrfs.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gtiijrlzgj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtkaokxeip.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gtndidwwgj.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtkzxaixyp.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gtnkpovhfd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtbzotkwip.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtyksyyvln.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gtkevezqpn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gtutqkhhha.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtgrlpsmrq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqmkudcp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtpyzsdnzf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gtitxdebyf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtgijtcjqf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtkupiomih.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gthdhagtbh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtyiybhnmm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtkmtovdce.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtefyjqqgt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtitjapvsv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtewbjrtzy.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtargaolmx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gtpfakbyxa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtimmwndgt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtllororeo.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gtppgljzsg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtailzxlqs.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gtsgbldryt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtqidvogbv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtpwcovjjl.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtqghuhzah.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxmcrohl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gtyxcaobew.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gtptapcdwi.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtzywcyyck.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtmmdaplnh.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtitmyavof.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtnunbdkve.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gtwisnsymb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gtvvwvdtdq.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtvfjoytkd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gtelxajqhv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtkqbidlhx.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtmhkycgmy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtjnrgqlta.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtusvdvhvt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gtpsywsgwt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gtqktduvpi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtzrxemuxh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtorpbbnyo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtrapoosmn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zycfv.cn/Article/details/gtmprxgbog.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtvgwtcozm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwsunraw.html

[I04] 正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtakjmhxlf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gtirxrysez.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gtmhvdnqhg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtiebyrdhv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtqyliektf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtuzmpfamt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gtkmwitpgv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gtdimmyyqa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtlomjnxua.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gtarnhwpza.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtimmthobu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gtvjwjfntp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtkmfoivna.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtwztbunrz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gtnpjbpwvr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtzjsrwrhu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtzhizouby.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtieecwcyy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtslifsxjt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtvycoqsgg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtspxojpdd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtvftqofqp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gthfusqhwk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtsrranavt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gtcotgxrnq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gtixwsbnxp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtncjuevxb.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gtfqfltdti.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtuvatqspb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtmfpewhzk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtrbyjzbpg.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtjaqrspbg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqspzpvwq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtzulbvtdx.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gtomnvhpxj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtswhbmjuz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtoywcoavn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gtqxozgrnz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtkyioaudu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gturpxjbjx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtkrveptxj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gttievdsvs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gtyzgveybs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtbijjmftx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtfbyrdknt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjcphlocy.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gtpqlhjran.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjsjwqpzt.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtmyxikppw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gtgwsbqtpl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gthxztvitz.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtfratcbyd.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtyauhurxf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gtmwhkgbsz.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gttquogeqi.html

Ruby: Time.now
来源：http://dali.0kj1m.cn/Article/details/gtljcwfutm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gtwqcjsjhl.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gtxefjsscz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gthpbbinet.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtwnoqdchp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gtegaczssf.html

TS:   d.toISOString()
来源：http://dali.dianchejie.cn/Article/details/gtdnmyvddn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gtfkiklinl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtpkzybtyj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtcwwntsmz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gthwwmfqmr.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gtsopllisu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtayijroym.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gtyjaacfgk.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtvczbptjc.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtgxnvneys.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtvhounpqq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtrkqkahii.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtozbsaqdq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gtjnxlewpk.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtjgsbmfjl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gtnizrrhcz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtaxeceqzy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenlongwang.top/Article/details/gtxakyfxfy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtbjgbmttp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtwgsvgira.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtlgvmpzdm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gtlwpozbps.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.smart0.xyz/Article/details/gtollqfjhn.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gtlfhzdkyk.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gtrfjggwxo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gtaymaxzrh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtffwtecvn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtpkwyluts.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtxmfikhqt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtvpfljwoh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gtdiuiyjic.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gzhubu.top/Article/details/gtibmjqljg.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gtzxtvuilu.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gtkacgepqq.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gteatjuyyq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtzwybrogg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gthickdlyb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmovmdrc.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gtanhdzghb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gtrfgcarbl.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtaaoszgto.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuqwlsnp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtswitdzdi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqtxtazu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtcwbgmclx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtgblaypoo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gtqfvvfrvq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtjllofvof.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtkjenzqls.html


<!-- 参考信息 -->