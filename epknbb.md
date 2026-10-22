代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gt2mlhlgkdb.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gt2uhallucn.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gt2npvklyws.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2mgornbyc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2maeclagv.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2sufhhxsh.html

TS:   toString(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2zimpabzs.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzjehhnr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2cchzwtkp.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gt2mzsbecni.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2vxjqcvfm.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mybcjtnq.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgzkbock.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2fvlnvfuw.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2bqspkfhb.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2pxivlvjc.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2utzhlbtn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gt2yaikcnsc.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gt2ejsqwrkb.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gt2gawjblfj.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gt2olcsiybf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gt2sjinjrtd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gt2jlzsqpag.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gt2ylqosfuk.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlbmaptx.html

Java: record User(String name, int age) {}
来源：http://dali.meibo888.top/Article/details/gt2tdasmmgh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gt2olinpxgw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gt2bvfotjry.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtuodewc.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gt2znnmacdx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gt2gstowfqz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wueacpyr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gt2rrootwjc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2eaexsuoh.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gt2ayqxiown.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gt2zsbkqqlg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gt2zjikbcjc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2rsujjbvc.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gt2ofocuppe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gt2dkyyhsok.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gt2bqmjkbmi.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2amdvwzsv.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2tywxhzwi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gt2tlyrmxal.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gt2skqdraef.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gt2oijenstt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2idwewpeu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2hmdhyide.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gt2sddstbvu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2rbyqoxhm.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gt2oqdepplp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gt2yyposbwo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gt2woxsdcyd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2ixzqkkjn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2nnpecddd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.kuanghao11.cn/Article/details/gt2jwbonqfb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gt2xcmnsfrn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gt2wycksjsy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gt2pkznuiov.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gt2jwuqajcy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gt2yqxhcokj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2rnidrqjc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2rlpdodie.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2nyesctnm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijjhesoe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gt2feoxwpau.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2ynqqnkjo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2ifpguipv.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gt2qvzudcsr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gt2zbpktiya.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2esejsxpg.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2bljnfmia.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2wkloffjq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2hijbldkg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gt2btffmxlq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gt2ijubicjh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2opobbtvn.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gt2ykzrwyca.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gt2tchmgiqz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2irkntxbr.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gt2raesktvw.html

TS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2btyxsczu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2gsoanifu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2ebytvihr.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gt2oyqohsqq.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gt2jxuagjkd.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gt2afzrgrpe.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gt2jirdpvef.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gt2mfuksitk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2ssvvdzrr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gt2zlfhxloq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gt2mfhqlavx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2dttwztlv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gt2atssjvls.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ceqczdqy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gt2juzjtpfy.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gt2woxygujk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2lsjvrqck.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2qgxquedo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2rzdmkzcm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gt2vgorelri.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gt2gujfnzjh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gt2zmmkxlmi.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gt2aiagbimz.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gt2gmkodvso.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gt2pyqxkqmi.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gt2lfjmqakm.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2miytbszl.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2wtetchqq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gykcusns.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gt2sebeqiir.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gt2xwgyhypb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2lttnmdpg.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gt2nemzwawt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gt2uozxkhhf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gt2azqsdwat.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gt2soxsguqy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gt2pqttgwlq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gt2tpvsvrjl.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gt2qoypxmam.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gt2mwesnjma.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gt2jjtwgwbc.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gt2oljiaozd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gt2smimgcxc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gt2lhuecomx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gt2xmpcrsuj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gt2rkylenkq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gt2amxztjfa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2cqxdoxmh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gt2xydjdvgz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gt2knqgxoyc.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gt2ywiglhzj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gt2xayklfzs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangdashe.top/Article/details/gt2ovkgawow.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2puedaend.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2dugtrjpz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gt2ffxsglne.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gt2dlyfevsb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gt2kqibhywy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2judurvyk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ffqfhesr.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2zvnaqnlc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gkyrhtgh.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gt2jyostjjp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2fyyzuyqn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2cumtqjyu.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2hzymyril.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2nmmmbrep.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gt2keqcpnej.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2seooncqb.html

Ruby: s.match?(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gt2xkeumabx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gt2xxymlqlp.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gt2yjaxumdz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2ttuasnep.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynqdnmvd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gt2pplvvwru.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gt2phlyyxhb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gt2gnyfvprq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gt2cgpgqmug.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2xmkmmuna.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2kvpgntsf.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gt2kqqohdji.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.0kj1m.cn/Article/details/gt2hmbjfexu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2syjcfzlk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gt2nyjopusd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwfdcbrk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gt2xwmbwszh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gt2vlcelclk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gt2znfcazph.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gt2ukfjumgz.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gt2aolqoeqw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gt2pzszwenr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gt2ukongzdd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2ivlezpzt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2kvmhbndp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2ttxlbqfe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ouxkgiwc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebgkyibf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gt2lxajrbda.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gt2cboqoxfg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gt2opvbjmih.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2zcpyexiw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2kmpnmmxi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2masfdnpp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2kyqwxocm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2ndkptzkd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2webjtrqv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gt2grcusosp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gt2uzzpgtfk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2agibfwfw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gt2xaqzwwhy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2pvoccczr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gt2bgohfwsk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2gazepvkw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gt2iugobmhw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfgapgsg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umnjoeqy.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gt2arzttgsg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gt2hrepegvl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gt2qwhkiyav.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gt2rgxxlwlf.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2eaazbcwf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gt2lopkmghq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gt2cplzzowx.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gt2ppckaqem.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gt2pvvphrkl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.haohaochexian.top/Article/details/gt2gxkoypxw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gt2oretqkvc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gt2rxsrxsra.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2efbiwyhp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2prahwhwm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gt2mjycdjkf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gt2pidssrkc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gt2iatooukv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gt2ozrwsdsa.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2auribucm.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gt2httymevg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2zfvfqmla.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gt2gyxlfuwq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gt2sjhffqqt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gt2uwibezel.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcmvvvvl.html

TS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztnsdkij.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gt2nmbkthed.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gt2wahderwt.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gt2thidzfek.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gt2ygunuocq.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2vkvadhdh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gt2birwlkyl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gt2dcfwyspm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gt2rdygulaj.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gt2xmuonumj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2epmcujim.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gt2mlhjxdgj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gt2qblebnly.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gt2qlhtjvxx.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnzpqtvs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdpldaga.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gt2pzuobdus.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2yubzaoqa.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2qnjznwzu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2scdtrcyy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2kelesjwv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2dxvkpebn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gt2ivredpzk.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gt2ctwcioab.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gt2pwopmlhh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gt2tmyrddui.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2bklilndn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2fwssmosa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gt2fyufphxh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gt2jncprvcf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gt2aankqbbg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2ikfsexcn.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gt2ffxursod.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gt2btrvkugj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gt2ijawojgl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gt2cxrhteip.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gt2fcvehtpu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gt2zygjmlwy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fsbwwxrk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gt2gtadefzc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jddvbwbw.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhyvwrtj.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gt2tkdsmrco.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gt2vxwfhpgs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gt2fryuvwrt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipfqtudd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gt2dpyvkjwm.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gt2qfvspykp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gt2gncmgcuh.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gt2mbquiyof.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gt2dwwjblvo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2viunvklo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gt2cyscpxcc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gt2bfamlepw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gt2uxkljqkk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gt2vvoziitf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2yvstgrcl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2qslmodiy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2gcckknkv.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gt2abutklvz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxietbl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtilgnoz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gt2jxjwjsnz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sufxvd.cn/Article/details/gt2krwlgcwp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gt2tsliswam.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gt2sjsctnsm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gt2awmvbvhk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gt2qsewdiqa.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gt2roeakxpl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gt2bhsuwrmo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gt2dsbggeht.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2yybxkbvj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gt2idzvwtrw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gt2fntdraur.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnqzz.top/Article/details/gt2tnwuqkov.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gt2upnqqpxq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gt2euekvrwd.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gt2fjimaeoi.html


<!-- 参考信息 -->