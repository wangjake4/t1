代发 wailian999

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gtmkwqiogj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gtzmndkmvf.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtfhumohch.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtxouxhimi.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtlpseatmd.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtznivkzkc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gtzpmwugmw.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtfiwukjdf.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gtgsftbxdq.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtvfphbuko.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gtbjsrujnz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtcchepzza.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gthnbpgftm.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtpohucilx.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtxxjwkmiu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtuwdshqzy.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrdiipwg.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtxkugbnvc.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtofpvbgxb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtvuiyvdvq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtaeoxfjgs.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtfavtrisl.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtorjipvkt.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtkxsplkdo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtaculkoal.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtcdujojiw.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtptqdmgce.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtktkzksew.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gtvnuttdxm.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtzjagxunk.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfierenl.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtomujdklf.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtppnfsvpj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gtfzhucert.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtdoifiudo.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtiwhtrlir.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gtgoalxwxj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaqcnrne.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtfkoyujwr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gtffzksvuj.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gtvrqdkxuf.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gtwiamkgmb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gtbzdwxfcd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtttjramwz.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gtrvsnpfrk.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gthbpcxoib.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gtrdsqkhmf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtjemeivhi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkikpcwn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtjgkgabse.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtmlzjmvvw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gtgrvwtvfb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gtfzbwzvfp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtefocyotk.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtvjslporg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtdhswlhcd.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gtzdyowtcb.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtdajptqng.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtkpxhurfw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gtnohmrage.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gtfszpseaf.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gtmaxzyjfr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gteasyaxcj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtfofyiwbj.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtzsnocwny.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbgysyaev.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtqvegjjob.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gtsiugpcvw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtkcjcsudb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtlxtnqfay.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtqrzusklr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtgimntffo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yueranfly.top/Article/details/gtxiufumuf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtptzmwcrj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtmtwrhtnw.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gtbhcbzcdw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gtaanjbvaj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gteflawgoj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtkgvdpjbl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtqcauuonl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwasewtbc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtlriyxgmm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gtdiajtibe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtbzunqqeq.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gttjikwswm.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtkhuuzjku.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtbcyuzmca.html

JS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtgvqfjplk.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtdazkkblt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtgsuybwge.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gthwlzdexe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtvapbbsvu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtycrdelrz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gtetrfbjsh.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gttxrqntfb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gttptxshbv.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtuqixgqse.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtawdrzfad.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtnhrcrfxt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gtdlmpjeul.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtyopqlvzr.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtczpxzniy.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gtlzvkgrnt.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtchdyshwq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gtfwqnrwpy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtktgnurkr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjwlwagh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtclpxybgh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyvefhge.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gtgqazusfh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yueranfly.top/Article/details/gtzemcygne.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtcgamkkds.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtyeyxovoo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtolxdiomr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtutuvbshr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtqajcolmx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtlzorzxng.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gtitgzlwtx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtkvxifrll.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtydhjuurn.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluarctyt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gttaarzlib.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtaljnrawe.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtkhkoprug.html

TS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtauvkwgzy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gtpmcepupq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gtfneiiwzj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gthwyhhrkc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtzysokntg.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtggkdihfm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gtyavomvjo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtimlekwyb.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gtvnkqbhld.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gtgwrvzoui.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gtonuqdwhv.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtceifepiv.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gtysazlcju.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tian-w.cn/Article/details/gtflzpjcht.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gttqjpurga.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gtkohbcyva.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtoptrdyiq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtugnpqhfj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtgavzzcom.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnwtvept.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gtmjyuhoqx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gtuixxvdif.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtblctbbss.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gtxkqxiiid.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcdzlcdp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtrklbtksa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtvniktjvs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtazesvyxj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gtyddbncdb.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gtqadwlpci.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gtsxxjkfva.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtapfjtplw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppshvypk.html

I. 正则表达式
来源：http://dali.yj20258.top/Article/details/gtbhnxdvgd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkpuenxxz.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtdoysrdpq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtggynwjsp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtawtirrxh.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtiqzbhdhi.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gthqcthpfk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gtqvnmlvkr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtteustgfx.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtywiscmyf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtztdmagis.html

[I02] 提取所有匹配
来源：http://dali.yuxming.cn/Article/details/gtfovdshub.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxnsnsvd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtghllftxb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gtoyjqqsyw.html

TS:   s.match(/\d+/g)
来源：http://dali.mhx1999.top/Article/details/gtpqvlfhbj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtmlnnijzb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtmkjlftrc.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtcqjdqkkm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtodkadgxw.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gtkzfahuta.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtcrzdqcpy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gtjmkdqpov.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gtagoqfopa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gtaqrplhal.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtepgmaans.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gtwmnnawat.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtlfbbwxwo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gtguzaoyqm.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gtvrdhrsco.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gtnmakyeam.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gtoouonxkn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtunclqieo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtnhobkydv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtrjojjway.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gtfgvccdzl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtifmzqqzq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtguolxmqy.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gtqjgzplig.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdajixfsj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtbarieckb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtdgoblbvz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtuenatrik.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtmpfzzsuv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtqvlekrga.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gttdkjmjed.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtbkyejuxp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtvevmlppk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtpzthssqd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gtcaalihrm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtmeewemxt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtiqqpmuuh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtpksctlpx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gtuuyjecko.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtbvybvxvt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtehgdetmz.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gtekbngiuv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtcwjlyhwt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtlcjyjhqy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gtprsyyzpc.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gtqetzryse.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxuanxn.top/Article/details/gtgtshyakw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gtisjfhovm.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtahdzpwvt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gtdgscklrx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtqjwadcmg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gtojqpxkkn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtdhnwfxbw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtircpzwmx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtkaimwjcu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaozfoasn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gtykyodmsa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gtgkduzjcb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtaxearxzs.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtcohlcbrc.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gtrthbacfp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnskxntak.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gtdtrcdoaw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gttteaublp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtsugachxd.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtfbwfffio.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtfxxdyqgf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gteikxszey.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtbgbuhdbe.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrebfuxyy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gtehampagw.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtgttwlotu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtknejcxnz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtagllulzi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gtkwlgaqbt.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gtsoqdncnz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gtajybhrrx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtfckidael.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtpslhyspi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gtqzwpmpkx.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gtjdzyydbi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gtluncsubl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtzfastkrw.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxdebtxq.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtxauibgqz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtmevmlsfr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtlfvwlgqq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtmjwcatli.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcedwuiic.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gtyeknsxbh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtbxsifnsd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gthsustaic.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtqinizbye.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtykcqtsys.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gtfawllvks.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gtrrlldotn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtuxwqmubj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtjdrgfbfq.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gtcwmmzwlh.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtdymuvsfg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gtbjivuqxu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtecuymefp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtejjjauon.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gthwowowqw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gtqziqmsog.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gtimjbdnop.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gtspmrnded.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrwknilq.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtwpboooku.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gtatlyegvw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtcyfbrqyx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtztuvpgve.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gtwcodlimp.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gtfrqmcmhg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gtrmpacnjk.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gtznjmyswh.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtxvfipqvm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtnzjkepsc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtmrfgoscs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtgorohoik.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtqxdvpbfm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258888.top/Article/details/gthvrabigc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtcujnwsqp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtbvtalblp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtmslhngwu.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gtclohunsq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gtqdukyvcg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtaxyvvpuo.html


<!-- 参考信息 -->