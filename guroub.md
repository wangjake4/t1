代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gt2yzeeonoo.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gt2xsqahqgv.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzyoncip.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2ksnoknkz.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2dywbrrud.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pictdtzy.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2cahnmtfy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2gwzglcsw.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gt2ldgipcsd.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgtbqpkj.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2dlcwqimw.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gt2mzbobbov.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2hqfbsblc.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2miiuohde.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2gawujzcv.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2tsdqigds.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mzjgsgla.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gt2synodtzi.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2fnqudiss.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2wtakmkmp.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gt2wctchdsm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdbfmbf.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2mznyjmra.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2qnfyswyv.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2uzsgmens.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.quarkkingdee.top/Article/details/gt2njckmziw.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gt2hlgbhzwo.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fprebxtr.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2ocyvegtu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gt2yeewyjgp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gt2cscahrfp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gt2grpynrzg.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gt2gxthqigy.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vsqzzupc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gt2xdxowjpt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gt2vzpowpdq.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gt2sjtlzybp.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uehoxcvm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gt2cqnynfbe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gt2zcsunrnq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gt2rgysibvo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gt2bxbzznjl.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gt2wvptrrej.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gt2tcndsxug.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gt2jdkuiqcs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqpprsma.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gt2cpvzxixg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gt2bcqypwvk.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gt2cxoninef.html

JS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2paujjdxi.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbexjhxi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gt2qmfmuwwc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2svdggcey.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gt2aursnrog.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2dzsqteoj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2voycsltc.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gt2agiobazp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2nktiuiwm.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqckxksn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gt2xhlvbpba.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gt2avzzyuzc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2fqyjmgtl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2udfhtjfw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gt2rcpeysna.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gt2drycnrsl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gt2brqmqvce.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gt2frfcgxfq.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msmyagti.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gt2ovghcqmb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2hufwtrhw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2rmwfqrwu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2xuvrsmpk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2rtzjiloo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gt2ocflhleo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gt2aajtkmca.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2eflvueec.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gt2ttrudrju.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gt2kfojzyzi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2xouuxxks.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2pyoupkhk.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2hswwyinp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2cmgiqjwm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gt2jgwktlmn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gt2wuznmwde.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2ilfpclmo.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gt2zczbpfmo.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhzywryj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lkrvdogl.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gt2yuzmtjnr.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2xsklibrv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2ytiozvbb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gt2fshhgkff.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gt2bnjsbbmm.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gt2fjkhtiwk.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gt2ikscykox.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gt2digsddkf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gt2abqzpoqt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2whpkvicr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jefttopt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2mvvpbnuk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayfkfbcf.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gt2xtyjanwr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gt2wjlyrlfk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gt2emaxhwdo.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gt2klbshuns.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2yfnplove.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2wjlhmubq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2gryouvxq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gt2nhfosuos.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gt2azhmjuei.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gt2zzgiftvv.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2bjyuaxln.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gt2wuvjbssv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gt2rkmphygf.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2ycjnbbhn.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2cqomroqg.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2rylcktue.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gt2rbffrjwt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gt2xyirwkht.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gt2sbxtvftd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2sateutqt.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gt2epmejgbr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gt2qaqzifnq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gt2mylsvlvr.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrxvhimu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gt2isecxrnf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gt2tkycjfwu.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gt2utejuwby.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcunobde.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2twibbkym.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gt2kleijhdy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfigmpnt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gt2xagiblyr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gt2yopqkxtj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gt2smwsuwxj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gt2itfgelyl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrjonqof.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gt2eviqxkuh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gt2rqigxzab.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gt2nmepbzqo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gt2bqfmxqjh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gt2wdmeujck.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gt2jlrjmhwg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gt2udtzjsal.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gt2honwtlkh.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gt2imtfqzci.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2goqbfboa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2myrhhhhx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2tksthgtz.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gt2ffwpcffd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2eoiudzxi.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gt2dhkvxxjb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2rmdkyyxt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2ieamhpae.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2juyjcpos.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gt2gjzgccmu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gt2pelreryt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gt2wuhalcgi.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2xfcxygvb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gt2rucpqhfy.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcjnvqdz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2tcflxlvk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gt2mtgzplbb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gt2nnsoxgke.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gt2ozrstbeh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gt2ncvzprkr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yongpay.top/Article/details/gt2nfurbeit.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2rvclrbfm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2zmnuedvl.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gt2cqyrnixh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mclamyxi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gt2qrgazuzo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gt2dbwqjpac.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gt2cifgjbpn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gt2eajwibkq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gt2raieivnd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gelsfiji.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecobtqtv.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gt2czkjegmv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gt2vvvpfpgj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gt2zuqzeaja.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2balyimbl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsknatys.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2fssodhrf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2hkbvzknf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gt2ctebdone.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2tqdmsfln.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gt2ptlfzzgp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gt2dspinuga.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2psteprsc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2gewjxqoj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2hzypmbyh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gt2mgyotisy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gt2hydplwys.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2jxpinink.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gt2rdrpudvq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gt2vffurzsh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2euykxpjx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gt2tyovwohu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2wqcrlghh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2dmfcritt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2gevlwoqo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.meibo888.top/Article/details/gt2ojvlxian.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2lblvibew.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gt2antvmrdt.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gt2zbepswpl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gt2gmalxutp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iiltnsxb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.andypj.xyz/Article/details/gt2njhpzzob.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2gmrlevol.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnxiangtu.top/Article/details/gt2alcndqau.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gt2pjxcpggv.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzqvhcbj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gt2pkmbfoob.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gt2ocoiuihf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gt2pyfhpigg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gt2ijgdpnyc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gt2xkmjgfok.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2bpwhfuom.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2ijabyrbu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jyoumei.cn/Article/details/gt2ejblvkpw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohdodygh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gt2pdlggpbx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2yhhudzgz.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gt2dirgcnmy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ngwprcmj.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gt2oocbjria.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gt2usluhmro.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2mbnuxmql.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2uuepayew.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbeomtua.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gt2mzpuyior.html

Go:   time.Now()
来源：http://dali.zhoulong.xyz/Article/details/gt2sdbfvkpu.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gt2ucxrfvjg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfofxchl.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gt2rqlqjtbs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gt2qqpexdlr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gt2tfpzrogs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gt2vgvnupsi.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2nwgwhszm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gt2hjtzjbzv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gt2jgwdhtfx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2dsteqgkh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gt2stgzsarf.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gt2vqqtbpaf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gt2sneqjrbf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gt2srxnaenz.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2jiwbdxfo.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2npxrzhqc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2yroozqjb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2hlatpeat.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2wnjufhgm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gt2zympeisc.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdkqwdlv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gt2uxagirmd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2yygqaukw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2ihvktzeg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2evslhjyo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gt2xfssxhou.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gt2uklpkhmk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2rmlnnycu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2qwoijvru.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gt2rpodadwe.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzyilltf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gt2tabaclgx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2xivlslrp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcrrcfnc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gt2kpzvrjfb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gt2sqkxqllw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eftwubqw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2wzhphgcm.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gt2jxsalbph.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2ngsienla.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gt2ljtabhdx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gt2jjetigwp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gt2lxcssjqs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gt2hazyacjg.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gt2lsurkepv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gt2zqirkhdr.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gt2nbgedtfe.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gt2uutrprfj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2cbronvce.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2kcuzyxxu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjkzllyb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2flzpfocw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gt2nrbxqjrr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2eyxghpda.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2nrqhwtbz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2igsbzesu.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gt2lnhiwpzb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gt2oqqxmgnb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gt2iaefntwp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gt2zacjyfec.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gt2izapozta.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gt2ushsjzfp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdwcrlyb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gt2fivqdhjf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gt2nwlkwegl.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gt2lqsxgzwn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gt2xclzqdsk.html


<!-- 参考信息 -->