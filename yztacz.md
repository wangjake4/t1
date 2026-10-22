代发 wailian999

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gt2hyzilglj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gt2apsqtrur.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2iscpwnyz.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gt2ngjvtzsz.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfdxrxok.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gt2dsektyoy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gt2ijfhwmjp.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omdbnnji.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvgpsomh.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqjxdhbv.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2mphfpukz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2jcuhysmw.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2gbphgqmb.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2lccgbmvi.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2ksfiodhp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2saaxhnxh.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gt2obupelpq.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gt2exyyqcir.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gt2cvxboitd.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2oemqyylt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2sfnlnnjc.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2slzxqxus.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2pgbdwhir.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2omnfunrj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2edvgasmj.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2hnuhgjyb.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2jvktxqmc.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gt2coaespfw.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gt2bcywriui.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2urwujdri.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2qdnxeity.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2fzsmjvys.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2ukwxibyx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gt2qztwscci.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gt2pkivbltw.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gt2dlvqyesw.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gt2jnavubng.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2yoatfilb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gt2zbpatutx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gt2hbvrzqkk.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwrmiaim.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gt2aqqlvfkn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gt2jiswvkid.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gt2lksjqkxq.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gt2nemyhdib.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gt2vyromdes.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ehwqpu.com/Article/details/gt2qpwinsfz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pksvniav.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnnbgtgg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gt2fmrcvrqh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gt2amuxywlq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gt2yngtyhfv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gt2lsslsiis.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hyozpxbm.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gt2bfjtoekk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzkdjqve.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsnunpkw.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2demcqmis.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2vdgcvlfe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gt2hemuryca.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gt2oebpgjed.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gt2boxzsvpr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2dpbcuerf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2udyyodmn.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gt2jwwxevdj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2aryjjzum.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axpjtvxh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gt2usblwtkp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gt2wwtobvbo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2hcwoyqyx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2ltscblpn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gt2snhmwrxw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.havefunace.top/Article/details/gt2djjtvbwk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gt2toqzofxx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gt2dvydhncs.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2xpllzumy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gt2jctlbiat.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2znickiyx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2xzzglado.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2vuwzjcrb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2ormjqwuw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gt2cbuwruqs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gt2beqxbjko.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2uqfsjqea.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gt2wwbabjuc.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gt2wmbxwodt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2olzukbno.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2tozxjtol.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2ryhcpyxu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2cjegxodh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gt2zxdyebzv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gt2jrbobjrb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2bcudbwju.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gt2xkkvsuhf.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2uuuigkgp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2czsdnoae.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqxudhis.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukerxkap.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gt2uwitsffw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsniyyxa.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gt2toghbhaf.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gt2asjkcymt.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gt2xcpimgnn.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gt2nqgfeyrg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gt2uqnmewov.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhviviu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gt2ltptoelw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ybvpnxgm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gt2lxuoiwqg.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gt2zmfhinki.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gt2druektfa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gt2zodhjxxr.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gt2rdscivvm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2rfnobdza.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2yndljwsu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2itdalwys.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gt2tkbfwhur.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gt2bkcjkmzf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gt2geobdhwk.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2znnqebsr.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gt2cigxrmrk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gt2rurmqltv.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2sscpkrgx.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwsmdmfa.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2tqifxiuy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gt2dvgcbwcy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gt2gknzhlhz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gt2namkmqln.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2gnaoratj.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gt2ewhpogrn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbgavmdz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gt2zgndnsod.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2plbbbdde.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gt2zpaimbex.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gt2ttapoflf.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gt2ayqlpqcw.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gt2adhbgpse.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gt2mfowxydo.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gt2eviyvegw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gt2xfjheajz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rknnftoh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gt2gfmbkvst.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gt2qhmxgyyu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2othjqsoe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2blctimye.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gt2mzboctfp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gt2vzchdhzd.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gt2stthwydt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gt2qkkmdygi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gt2efybihgu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gt2hfunxopu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gt2fvipibqu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gt2mobfirfw.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gt2srnxpobm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gt2sobwcuxn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkdlzjsn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2zaaqnigx.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gt2ismmfxfr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2osbounnv.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gt2unioutnn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gt2cftzyinj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2luhdtfxr.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ykafzblk.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2deaajtpu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gt2kppkqbxc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gt2ggpwdgfr.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2vncnbxok.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2njetpftm.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gt2loefpgnw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gt2itirurxi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gt2lhsrzfxu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gt2yluliifq.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gt2osvagicj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gt2ohrkoimb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2bqhflccp.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2rjlquexy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2csaowgpp.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gt2hcwrwplk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gt2jjxzmfpj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dttlrsus.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gt2yqpvlrjt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcrylbub.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gt2bibuoaxk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.quarkkingdee.top/Article/details/gt2zwdfdnpf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gt2odvvgwbl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tianlin.xyz/Article/details/gt2kpmacjwv.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gt2wauydszq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gt2xwajdiyd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2zbplqdah.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2oemevdbr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2nloyxlel.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfwhjclo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjkopeam.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gt2ripgfmps.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gt2rvumdhfh.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2jazikkxi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gt2tyvxhduc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2icsdqsbo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmjmkxwi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2rwjmoevw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aizwys.cn/Article/details/gt2vpmgxnqk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2rzyvlbwx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2psrbomxg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gt2vgwifmuo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slymcerw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2weovlolz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gt2wiupoxag.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyahfzrj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2hnciuvje.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2skewvtrl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gt2ayumjnoi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gt2fqdafgue.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2ftbvnlkk.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gt2cdgbblnh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gt2dwsagapf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2rzbtrojm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gt2istjmsbw.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gt2qahpaylm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gt2pcsbipfr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gt2anjvydwt.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gt2ocvrdndm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gt2mtltwlrj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gt2eqcengsa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idbhxdtn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gt2utwieedv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2mzilygrt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2nurjdrsj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2nekuzujc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gt2ymsxxqrn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwuigoyp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2vmtwthob.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2dbmshtrk.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gt2olmllsym.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2tuujydxx.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gt2aavwpknz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gt2ameitzwm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gt2binmwuev.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2vrpqihuq.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2bcnaihzy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2roztqhqe.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gt2uzijheah.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gt2ipfdfayz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gt2jjzjmihu.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gt2cggdgaua.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gt2jygybgrm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2oewcvsrc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gt2wmfdkucv.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gt2evpklfbl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gt2tryyxvna.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gt2keaeohuj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2mlsnlsda.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbkohppk.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gt2drjqkkla.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gt2vweocwob.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gt2yajnmmzu.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2gsdchujf.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2xdrbxapj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2xlmsroor.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2bpjrwloy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2xqtmyqyt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gt2mujpkqwd.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gt2vrylnxsq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2qcouzruc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gt2awexdgqo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2deueuvmr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gt2qrqauotl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gt2ibgedjgk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gt2xmxbsjxh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2hspuaits.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gt2bffipnle.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gt2qobghcof.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gt2rcmtnfjq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gt2aepurdmw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gt2fxdtsaad.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gt2acguqcgp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2qlmjkygy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gt2zvonlfaw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgoefhfm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvtajmax.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssmhggtz.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2lyliuevf.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gt2egcmeyne.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gt2oegbajdj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gt2qjrrlpxm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gt2gciryhil.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gt2dqqbighq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gt2lolddgol.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gt2bozfvlgj.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gt2fbksdphw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gt2ktmowuoc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gt2nlzmsfkt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gt2dbgmrjvk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmhtsikw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2wlchiayb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gt2kuhhvmiz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2sfopxjup.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2plavmlfu.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gt2xagozkmq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gt2xgobczqw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gt2zeeguwqg.html


<!-- 参考信息 -->