代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gtyxiojqlv.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtmxiddkec.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtrkvgydnw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtgfuwnyyy.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtxoaifnpa.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtqyzxdcvq.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtescvtqpu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtftecvqes.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtncpsizhi.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gtyojggvtq.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtmzwxzuvk.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtzljxjkre.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtakvupcdi.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtkjpiyxtb.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtyiqbqbbl.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtlzhtjwwc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtoiqmqcio.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmcqlatx.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtpjeouvhb.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgzgeosh.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtnjolquih.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtgazjfuty.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtmybljwkw.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtkiitkfmx.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gtxdtmrvgv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gtbzafwixu.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gtruyquopq.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gtnjpzckop.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gtfjmnxtcw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gtdawobudd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gtrstakppi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gtuwdhvuua.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gtpwsdvqwi.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtymzldakk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gthwtlzayg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtnggevcrr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtxotqycdu.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtbikoibml.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtjyaapgvs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gtbixljnvk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gtwclvrcua.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvmgbjsm.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtoxpabdgt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtjrlpywdj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gtzbksposc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtyzqmtphf.html

[G16] 对象转数组 / 字典
来源：http://dali.fzhhl.top/Article/details/gtqwlhodre.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gtrodbrmxb.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gtnnvxawov.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanclqrfd.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gttawfrbfu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gtxdybbxmn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gtvcusodtn.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtlelmdlrj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtpvzsgwrm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtemhjixvj.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtfjujmvyz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthszsomhb.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gtgpptcdnz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtfofhzena.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthtvibqof.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgseumdks.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtenzapncu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guowangkeji.top/Article/details/gtfgdiacwy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gtyfpobtxh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtawrrdanh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqudzabe.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gtlgszhlxo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtogdbbnah.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtponddoet.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtrdonfslk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsqhdyyto.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtujcrrhcg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gtaabteoxk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtbgewzvfs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtbzosjnhs.html

[H03] 主动抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gtwiqntzed.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtztznaouo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtikuomduh.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtrzjroedr.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtvrplyxdc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtghbstdiu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gtxcdlaejc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtbvndzskx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtyfjzvrkl.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtpljimlso.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gtrbudfnfe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtehnmckul.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtbiouycta.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtbhzavuvx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtulyrwlfy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gtjxcldvcd.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtypyicmfq.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtsszzbday.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gttvkigmui.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtgcgjjzbi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gtterlmayo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtpcqhavjq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtxqnfoikj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gticovfnay.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gthdwznnng.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gtidlmbpea.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gtyrfdrnbd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gthtnkvvrh.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gthxlytcpi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxykdbvzv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtgvwtubak.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtkuctjogo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gtyibskewm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtpqwdremm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbynmmrso.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtnszcapev.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gtfoynidoi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtenqymrrn.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtyuyiienq.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtmbwrhsqx.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtdmunimax.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtftvthkke.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gtxygxlgqg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.haohaochexian.top/Article/details/gtshkyhxaz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtbvbpbvgv.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gtkvmkqrwz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtwxrswebm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtnumwwgst.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gtblcsakaz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gtxavisoim.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gtpbmvetbl.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtaabaxjdw.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtxcsoxvzh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cdnleiting.top/Article/details/gtllofkzig.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gtjwgdrrbh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtmmqzpmgk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtlgdvpxbl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gtgurndduy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtglllubtl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtlubtxnjq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtzjxflkav.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtoqnkuxwq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gtgmyfiruy.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gtmctihxen.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtnhjxiiso.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtekqbepzv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtvfyhvcju.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtuexteenx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtrmghffdn.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gtmdbtfqtb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gthdqvhunl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtmyryhael.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlaorfnta.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtakxeosww.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxnnclnrw.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtdrzosjdm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtluaqcrtw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtrddiroxm.html

JS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtpwjmqufp.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtzqyzacpc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gtzyxfjaaw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gtfrbfdfsp.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtezcjdwwc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtiugqggpi.html

[I02] 提取所有匹配
来源：http://dali.zhongyouzk.top/Article/details/gtajefdqdd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyiizpzs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gtfftjosbi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gtkxmcxxao.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gtxskyuhda.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtxalumpcx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvfpffsd.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtcvokmmeh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtawkeozgl.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gtunvvukbe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gtjlahvhdo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gotoacloud.top/Article/details/gtyynuxyrk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtijomngnt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gtzmnaegin.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gtczneeato.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gtcubilatg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gttkbydewq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gtbcnymqjf.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gtqvehudzi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gtjiqbkhvn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtzbsbsbgu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtxhrxbwoc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtoljbochm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtecjnevjl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gtnwmyypqo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtwihuddca.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtlcfdxtfa.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtifjdyogo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gtcrvodfjo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtkitwqnst.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtxygjhskv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtwknhlcya.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gtivymqdin.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtbvbzoenj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtmuapermm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gtjkqbjeka.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtlwuqnweb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtplwdaqil.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gtyrsmgvum.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtxeahoaha.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtuoaovyeh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtpqtfxpye.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtdqkdcrms.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gttglwlhyi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtynmlimfx.html

[I07] 忽略大小写与多行模式
来源：http://dali.cqqwz.cn/Article/details/gthczjikht.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtpksuggwq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtxotuqlew.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gtrltpaorv.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtmpifsjlm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xinyue.icu/Article/details/gtpnacfafs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtffanqowc.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gtfslnmlcl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gtorumjdqx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtekdbghdi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtjutdvlgm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtqlckkmgc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtyrumaxfp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtpwifcnjl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtahxujhcd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gtdytrcvjo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hammf.cn/Article/details/gtdictcwwc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtggazekif.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvzynehsw.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gtoijukydx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtczjenwus.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gtnwwvqymx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gtyoloiuzx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtofqjppvi.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtgjktnbfp.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtgbavwjyo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tianlin.xyz/Article/details/gteegratdu.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkexdnrhs.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhfuksls.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtgcqbovbm.html

[J02] 格式化输出
来源：http://dali.redwolf501.top/Article/details/gtkxguugto.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtdqfzbmoa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtwhudolch.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtjksvspmt.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gtdkbyetzn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gtdbvknbca.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtqmefquia.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtqmymhcto.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gteccgrexq.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtcsldjcfg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtdsfijbpr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gtqbvhphrn.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtljkhjvif.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtfnwyqdal.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqndzedg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtkvgqnzba.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gthmzqkkqv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gtuevzswsp.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtrcnwfhyk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gtbyytxzxu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gtpqtnblvk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gthztrzvfo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtykntmtju.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gtvuxtoebj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gthiftycoz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gttipafhnj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gtvlckiauq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtqcouybcj.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtornbxtot.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gtzngjltml.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtivvarcyl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gthnzwepkv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gtvydlbsnh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gtjjdxajdp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtvploljxy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtclmlhjfd.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gtksodaufh.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gtjfeuxmkq.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gtmozgfkfn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gtspfskdal.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmluikwn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjfpsyul.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gtoaqvezko.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gtcpiynipi.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtnjkfyeqt.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gtvgycjczj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtvaqfsgbm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gtgaflobng.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtkaoxffib.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtvqxaqwae.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gtztwkviok.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gtgmcslzid.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtbylhnmts.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtogwhwjjj.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gtmcvqvqis.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtwwplqliv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtuqboiiwe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gtdhrexdid.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gtciibtiov.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gtutlayydt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gtwjbtooys.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtvifxhrxo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gtbgtwgmzm.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtdriybgtu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gtdhjlzxdx.html


<!-- 参考信息 -->