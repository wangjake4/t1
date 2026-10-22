代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2hhxipovs.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2dgwxpccj.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2gqlklowd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2jpxjsljh.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gt2qwsayqzs.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gt2mphwnqpd.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2koketiew.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gt2raomoioh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2zjwpomos.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2chggyqga.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2yqngjkrr.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2mhxbamsl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2prxclxcw.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2zufqgcaj.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gt2bludwhbe.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gt2uyzpxlkf.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gt2novitqec.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2kasdfkfh.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2shumjick.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2sgejsaqd.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2bybzqpxu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gt2tyofwwfb.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gt2dkzvprwl.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gt2hisslzni.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gt2szbkunof.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gt2dgumfnel.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gt2pnkcpddn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gt2xptdfsjj.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gt2pouxnnxj.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gt2gnexdchd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gt2usrdnper.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gt2nwtsairj.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gt2hkqhjlqq.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gt2mqppufzd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gt2cvqcwzep.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gt2rreyhdng.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gt2noquepaj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2iezuxyul.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2jtolyare.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gt2hyornwlq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gt2opmvpuvr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2dkgrqtjl.html

[G16] 对象转数组 / 字典
来源：http://dali.ppjwa.cn/Article/details/gt2slbshayy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gt2qrlkptlv.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gt2atqedxfn.html

JS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2lgxgisba.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcjmvbcc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtcpywga.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygsnzwyo.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2gkopcnsx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gt2fsnuhkez.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwvlmmmt.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gt2ffshnekr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2pekmsnek.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gt2qogkebci.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gt2inpzkeqn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2reoxjafq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zqfmnmxx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2tcaunuiw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gt2kergkamm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gt2xbrqcgwq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gt2eugbxmwb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gt2gmsylgaj.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gt2qhzxbeew.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gt2rlpoybjb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wludjsbx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2znrprohf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2rdhwjoci.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2dfvrimqi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2cesxjzhl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gt2bhmyhmng.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2xqtpjhmh.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gt2ecoryxbb.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gt2oxftxlya.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejjhihvr.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvnjaogi.html

TS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2xsyasstp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2fsxmiato.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gt2fbfadpic.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gt2azdxkrlb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2xxxlnwme.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjzeubhu.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gt2amthcatf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2ndgtwgtm.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gt2sngfbdjk.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gt2ukuperjn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2gcuqivyn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gt2rglrwcov.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gt2dezvomnp.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gt2bycytjky.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gt2wfpaelpi.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gt2qltrywmp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gt2uulcpluw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gt2nwolwvim.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2byinxhzq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2zfttdovp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2bsawcuto.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gt2iwirfrdg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gt2eczonmzl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cezmlttx.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gt2surxyixd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gt2ujtpycfq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2lddugize.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gt2sksklzjh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gt2ibwowuvx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gt2jtqwzcro.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gt2ywsnowaf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2wdoqfqeb.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gt2yrzomjtx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gt2meahbili.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2euoqlyzf.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2krtylaed.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2uydsgpwq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gt2heitxmuf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gt2rfxsgupu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gt2indhcuki.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2qwxnrfjn.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gt2mdhawuhc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gt2xbmskzwi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gt2ikxninrh.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gt2gjqptucb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gt2tngkvfop.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gt2ckqorhdm.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gt2fjcxnemd.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gt2kwzxzajt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cdnleiting.top/Article/details/gt2unasmoaj.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gt2kxcjejfz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gt2dlbvteqq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qnjiqjrr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gt2azlgxlvl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gt2irdqxuqo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wnqubprb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gt2gepdsuvx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gt2rxavteul.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gt2sulorkfd.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gt2dpmpgdkf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upyzjkqs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gt2doiqcpot.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gt2lngfwims.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2yafqbbpw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gt2gmxvfbyy.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gt2rthhldvz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xprzeyfs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2mvckpvag.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2tnmgkykx.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gt2gohznowa.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfzovehz.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gt2svngppbu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2wjkoqwsy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2gmwbgnoi.html

JS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjnuwcrl.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2aaujldkg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gt2mnzbekwg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2tqtngcst.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2yxzppvha.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gt2osvgqoxh.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gt2vanmnolu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2iptjprua.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gt2cibrlxrl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gt2qcmmnazx.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wahpkvue.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2tomzadto.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2jqxtollp.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2jfqstgwv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcooamqb.html

[I03] 提取捕获分组
来源：http://dali.hnxiangtu.top/Article/details/gt2vjklfxtz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gt2inyxjsft.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gt2pvbqdgml.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2budpyiik.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2yheymqwj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gt2rlqhpbxf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gt2cclvuyna.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gt2xireptjn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gt2hyqdqrmr.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gt2qmapffiu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwaasgeb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2ygwcjezh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2qaonshuc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmyeaszm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2oqsvwzcd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqojeney.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gt2pjehlvkt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2msfrikjp.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2kfwouuhi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gt2qdwpilcc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2vkcvplhb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2enfjhvvd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2lzydoayn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gt2twfjhyqt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2fhxasqgt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2jhxsmyjo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gt2nvwymdfq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gt2okdpixhq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2kmoatwmr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.meibo888.top/Article/details/gt2pkphhtln.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2fmorehwv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2puxukyoq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gt2gnbkeowi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gt2lekvgmta.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gt2dvezjmtr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2hwknqnid.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gt2utrexrds.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gt2qgepxdqb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2sudffssd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gt2bmiwndxv.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gt2rnvzigrm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gt2bsjvqrxa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gt2pepblzfu.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gt2hkdmkajv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cdnleiting.top/Article/details/gt2kmfxbysb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2btwpbuif.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gt2cqckkote.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gt2pntysnty.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2myjluiyo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gt2miborenh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2apzhaxxl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jianghu66.top/Article/details/gt2sicreddz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmhlujos.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2doalascx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2gituonig.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gt2zbibrcle.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ludbjpkk.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gt2mjdblalp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gt2ipwqxuvn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2jehfylvt.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gt2rouspkum.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2mduypoxw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gt2vhihkayz.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gt2lskzckur.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gt2oqkgkzlm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gt2jrnznqhb.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xaqiiatw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2nbxefswv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2nzzlwweq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzpmsiej.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqijtkce.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gt2kfpcfpro.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangdashe.top/Article/details/gt2reaszwxo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2betpqjhg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xylfe.cn/Article/details/gt2grynklzi.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gt2mocafoll.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2ptfmtidf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gt2abbrqplb.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2xmnbjbiz.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2ggsmujnk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2iptwyxch.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2ksnuuxcn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2nepnuaay.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dianchejie.cn/Article/details/gt2yfhloulu.html

[J04] 时间戳与日期互转
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrgptcut.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2ucaqaydx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gt2tncdcsin.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2eoynrgrx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2mivwebyn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2wglmlwyf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gt2gxhiibzv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2yfehbfng.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2mveqdchn.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gt2zgiwvyyq.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gt2guqvgfre.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gt2aoylpzob.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gt2hymtxhuw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2tmcoowar.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2kbclrtgs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2hjqrmten.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gt2obhmfoyr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2knhcfzvz.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gt2udhxbrdr.html

Py:   (end - start).total_seconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2ptwefixu.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gt2vopcfabo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gt2iuagqbdt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gt2zfxbnapz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydbsdklv.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gt2rzccdczo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gt2cabowebz.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gt2qfwcrbnu.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gt2vgygqiwj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2spkedrqt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gt2wzsblddy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gt2tuyqahqv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zznvjhyh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gt2ahceeycc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gt2etswhivz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2ramrhyev.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2vhfxivjq.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gt2cxqorlxp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gt2bvvwqmld.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.vqdsnc.cn/Article/details/gt2veolfwlj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gt2nrxmttzm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gt2jqsaarfd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gt2mlcgisjk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gt2pgxcmxmt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gt2nufaaddk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gt2thdxaytc.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gt2yqcfwfub.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gt2ljkcojem.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gt2hezatqcr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2dhlvzgun.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2sggmkrht.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gt2gbashjqo.html


<!-- 参考信息 -->