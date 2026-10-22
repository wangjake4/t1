代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gt2ckecsxpv.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2yukvfgsr.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gt2febsdfqh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2lgppdjqs.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ngesgmqn.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2kvkjmtcb.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucqxvkhx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2ievidsiv.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gt2grmpebcm.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gt2cbzybjrk.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gt2ufxpmkdu.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2uqvdfttg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2rjqvekvp.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfagrafs.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2adtnohmp.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2stmrbcvy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2swvlngmw.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2zmtqpunq.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gt2hwujluws.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yyzqognz.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gt2zzngrgau.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2xxtjprlb.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2dctdkqpp.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2tpdfxeky.html

Java: u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2maorezzn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gt2myhwqlno.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gt2ddzrsskf.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phnzvkdi.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gt2ysvordca.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gt2mbyhebcv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gt2feeqzpkl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gt2ojzbmvcd.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gt2qhtvnihl.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gt2kidumuvj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulaxrcyg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gt2yoxajptg.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gt2tlyupxql.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gt2zsqlqwrh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpxyrlil.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2htkkioef.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gt2uxqxcfhi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gt2hvmvnffz.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gt2gawnkrjy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gt2jeoxaonp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njsvhvkq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usmwageu.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjmtlunk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gt2wlywbckx.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gt2ueioglyd.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2jmfxfhli.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2yzbzxady.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gt2laocdlen.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gt2uudevnzk.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbgkhjiq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2frovfarj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2dlhqomcz.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gt2uekeysuf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wwnszlgr.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gt2fakzejfk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gt2wphsszbd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gt2zkknbgtz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2zvqogkwk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2dfluwyhv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gt2ozwtfdwg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gt2yhlgcvtv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gt2xygczdon.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gt2kogzdhgf.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gt2bhrcauqj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhxjhzlp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2oyrntlxm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2djrxyhru.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2pfzexuxj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2dqpoehfp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gt2edpovfkr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gt2wywykvgj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2ljhbgifc.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gt2qzlhbwpa.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gt2bdqiuank.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrbcflzs.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2tspwuikf.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2jqjigies.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2ywpnjlrz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gt2wiatcqcb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gt2ptqdwiab.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2wsnslkfp.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gt2gnqlafui.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gt2qdehmbli.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2ngqwfrqa.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2vioxqdsv.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2ibnzowca.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2tabuiajs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gt2xsjryecj.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gt2xtmldslc.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gt2houbnpqw.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gt2pfjvnqgo.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gt2ncktjhpg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gt2xsvgcilz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2rqjstmbj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2jguwaotd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sxryk.cn/Article/details/gt2hvbxsoxg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gt2jilvpldl.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gt2jqiwsspn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elaaakha.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgngpkzs.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gt2zpupmkhp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gt2akseiirm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2qwshufhb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2ecshwkhs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gt2owpnrfgn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gt2plvbueix.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2kchpjwwr.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfvoowvf.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gt2qadmnibi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gt2julqaias.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bozfavrl.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2mxssncib.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntafvafp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gt2fsgeomkb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gt2wjkdajhh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gt2ryeidbwd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2ptdlklpt.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcodxcik.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gt2tvekhmjg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gt2xvoxhlyt.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gt2unjuagmz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gt2xaetykia.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxzdgtgz.html

Go:   err.Error()
来源：http://dali.xylfe.cn/Article/details/gt2nrlqrcal.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gt2wsmkdwwf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srjlulgs.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gt2pmocspgg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gt2gmrznhmw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dntkpycy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gt2gmcjlaqa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gt2ajyajdmj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2flkxtqfy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2gpmcbidv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gt2yhfqgpyp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gt2vnxgdhdb.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gt2ggzwsyer.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gt2bwdpctqy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfgfjcff.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gt2ekcxncav.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2dsrhejnb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gt2gweozsjc.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2siaxorlh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gt2ysdueutd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2eraiwcya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnahxltx.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gt2shfjpbqq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dstvlnpn.html

[I01] 判断是否匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2zxikexyx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gt2jnxppfyr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gt2fvcdjfqu.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gt2dlvahjuz.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2dkuaqazn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amhsefir.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gt2huyjplgn.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2ffgcmwce.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gt2eamxkykh.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gt2feknuzhb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2owoldtas.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gt2pudlicvw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gt2inzbfvro.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iybfoldo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpikoata.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gt2qmmjauch.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gt2gclrkzei.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2adibcbww.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gt2oafeitey.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gt2ddrkyqir.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmrmwdhx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gt2lmglkobe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gt2rmxteftv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gt2sftacvau.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gt2mmxqdinm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gt2ooowkdle.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gt2ayoomdmi.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gt2qzuanooa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gt2saojkkfl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gt2agehxjfm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2ehzjlavh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2seocbcqw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gt2xeltaaru.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2rbliqulp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2mvveritv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2zikncrxw.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gt2strcsxka.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gt2dckyxwfg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gt2hpetgfqw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2uixlobwe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2ufduowpy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2dnvrixxn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ynwprbqi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gt2kczdwflh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gt2dmvuevsu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gt2plxcbyec.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2egxycfcn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gt2rrnhxhil.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2rpfaqslm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2dcelnfwm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qugunhbd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gt2eaceahil.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhbezgtx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2unnzjkft.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gt2hgrjxjnn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gt2joarskce.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2zvfuaxle.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gt2vmywjluo.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gt2uxizrjvd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gt2mpkxszsk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gt2yajrqtwd.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdadvhsf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpbgiyic.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gt2imvjbqix.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gt2qllstumt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2xdwbbjxg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gt2dnbufcgc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2jdckizhp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2hujtxylx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nsbnmqbt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gt2moqebfsf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gt2fjgijovu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ujmifsao.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gt2dipunfgm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2evrxwbuc.html

[J01] 获取当前时间
来源：http://dali.tianlin.xyz/Article/details/gt2lenfpvsf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gt2xenuvcja.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gt2uaowrnhf.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhdrnihe.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2wlrlibfq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2itegybfw.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gt2gugupmfa.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gt2tfulbmxq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gt2mvenohxj.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2omjphwpw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gt2hqdgkfzx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2gzhfrvzm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gt2oiaiwdxo.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2zksmyund.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gt2oyjiwmie.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gt2btnidego.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2uvhlievr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gt2qcecxkig.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gt2ksxxzdzn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gt2dsxfuxwt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vaoyeabw.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2rkxalqrx.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2jketldjw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fflocunn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2ibbcdoux.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2tgtymazj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gt2sfpwdcbw.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gt2lpgetzht.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gt2zpsrehns.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkfvpxzp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wynqtprq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gt2pvzwmlic.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2vpuzilpp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2odescvxx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2duszrwkc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gt2mjifuzny.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpcdepen.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gt2vnagclje.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gt2gzqlkqsy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfhnmxuy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gt2vjgcyhpp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2veeqvejf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gt2rscqdmfn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gt2hbosfkhp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2plioaxix.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gt2fufjtcjg.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gt2fqjpzdxd.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztvsqvsj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gt2kxjdggeg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gt2kpsxrrka.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gt2iekyhfza.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gt2lnwrbxlo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gt2wwfaqgdk.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gt2jaqoflxe.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gt2ckxkqejo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2zryxdtmv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2icbdytge.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gt2uuwyymvy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2ojtsowds.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2pdstevbb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xptbgtai.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2oyyxudxl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2tkdjpjhx.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gt2xzseacfq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xinyue.icu/Article/details/gt2atyiuace.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gt2iekubbio.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gt2vgmibupe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gt2ishuygrk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gt2bwjukguy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gt2pjtbqove.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gt2aqghvfoe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gt2vzyrmlxk.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gt2evtlfyeb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gt2ewhzklli.html


<!-- 参考信息 -->