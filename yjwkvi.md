代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gt2omyjdfqq.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gt2uknriskz.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gt2fvvotzdh.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gt2yturpbdi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2jreskqmh.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2aykawkal.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjiqgaxu.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2khhrysmc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2tjvwafzs.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gt2sdqjqgpv.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2igilmaxq.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gt2cjfheztg.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gt2xulpvsol.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2cdastfhc.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bombxngk.html

TS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcpuhqta.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2hepntafp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gt2aaoymuol.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gt2zdookbfc.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gt2bkeancrs.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gt2svvuxibs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2skofohyq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gt2zjiekqlq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gt2pbhqiuua.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gt2nzvbzfbj.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2drzlovuj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gt2aixleaqc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gt2rjjnjiev.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gt2duaigfak.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gt2ankhsijh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gt2pyypozzg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kcvkvtjg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gt2wznhssmv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2pgnalapv.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gt2sbxhmzay.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gt2mzsbglle.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gt2vayvlldc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2ynqdbadj.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gt2sfwtvsbw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gt2fefojpsc.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlvfnpbz.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxjwytxj.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2avrxvgcu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gt2xfrnclcl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gt2pekbmcey.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gt2hivymuph.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gt2szxexwwd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2hqlrwxua.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gt2weeoeizv.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqahnlmg.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gt2dsfteebd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gt2pnfoslzo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gt2qltobjyo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2voyjfiml.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2ufvymdbq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2tzzemiim.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbvdhctf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gt2gjzfcsuc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gt2zvkybnzo.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gt2ejfudvqy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gt2lajizoue.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2dqulwfjn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruknwwsn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2ixqjjuxw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2sqzfobdu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gt2ridrmbos.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gt2cfjqvmzs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2pvwgrjcu.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gt2ibjyrxbx.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gt2igaokdgc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2pmgqpmyx.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2bbmpooza.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2unoryvdb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2ecnurmwi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzyphqps.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cheryme.top/Article/details/gt2sgzukits.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2mbzljfqf.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gt2shhrgund.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2rcsjbckm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2tdosdeov.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbvrbnny.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2apvewrrg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2prjrickb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hammf.cn/Article/details/gt2ummzxlvu.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gt2foklhdlp.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gt2usilmmmp.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gt2gmzzieyj.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gt2avxegpff.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gt2xwykyjrj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2yobfnnvi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2nxkijtog.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gt2eohrjyyd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gt2ucinuidq.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gt2viahdfow.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfaoxltx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.haohaochexian.top/Article/details/gt2jpeigyzl.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gt2lskuewpr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gt2iqdswntn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2gshljtsj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2intexvgv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gt2fwrjtvok.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gt2rasdrkyc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gt2ymfslhqk.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gt2yrrzuzxc.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gt2vytfskue.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gt2mvuvawap.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2bkcwivnj.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2scccztkx.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2krondclp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gt2nuakhwgo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gt2ggnbzbos.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gt2rkhxnsub.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2jiqfhpwm.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnjjprkp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gt2mbixbazr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gt2ttumprxu.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxvcvbez.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gt2gpratwrz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gt2owddystx.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gt2wqfdxwpg.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gt2qaivqqzr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gt2afoukuyn.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gt2zrjalxbw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gt2cxltguea.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gt2viknvcix.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytwffyib.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sskfmkoh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gt2sydjofnj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gt2fnoggslh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gt2icifujmy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gt2kngtzepj.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcngndux.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gt2wmvlntlt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gt2hgetvkqx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gt2tggusbmk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2etnpdisg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gt2adflnvck.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gt2yqkffzna.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2moibdhfy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2cnrqmqzp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2jfjyiyqz.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gt2txiwvcur.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2mvxwcvam.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gt2jxqbmigm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2phqiccix.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2klcqapmr.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2czfcgfnq.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2foyimhmq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gt2fetmghee.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqqkkuiq.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2izcfiaeb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2ovnduvqf.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gt2ohktrtip.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gt2krbpaxhg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2wqpdghgc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gt2ktktbrnf.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmeduwgw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2rwztcuor.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gt2brhmbmni.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlkhqozv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2zteekhcw.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gt2coaqbqtq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gt2cwrkwntv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gt2ajsnvnkn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gt2ffyajbss.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gt2higbnuyi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gt2swgjcdhn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gt2uxqdbmyz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gt2ntvwqqki.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gt2itanzosx.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvdiacen.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gt2fvvlxpbv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2xxppbfmk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2terhkoox.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2rsahbatc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2nyuatqcv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2vzbtxgut.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbnpuumh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gt2bwrshuwu.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gt2lqllbika.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gt2fjlxwdnd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2mqkoekcy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2waxuwfrl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2tbcbrsbt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2kmndqidm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2suxgaxwq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2nazycklm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gt2jwjokwym.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gt2jikegige.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2zumwdmlb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gt2kvtigoeh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gt2zucgdcol.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2aswvdihw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2cfqpoxjh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gt2staurljy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gt2iytoewci.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2qxyzcvph.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gt2tmhrrnbj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gt2vosoonck.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bimsyzej.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gt2zurpqdop.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gt2vhnrrcno.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gt2mujmywgv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gt2rtrwujcs.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gt2ygdofpfx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gt2znijnchj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmjafat.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gt2gouhglnd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gt2ilpalnrp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgrjheqw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gt2dgbbahkl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2bfitfnns.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gt2rbffiday.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gt2nruqeosp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gt2wpnkxich.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2zzrezmxh.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gt2umqkstvw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2gsyqxcfb.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2hwjqdomv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gt2svtschlw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gt2xkcxvjjb.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvkamytt.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2xxouuahz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gt2yohuxkon.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfjxczqv.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gt2dtupyqcw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gt2ammjpfjy.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gt2hwervtsa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2goeiyydv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2iroizfip.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gt2lfbccfsu.html

TS:   d.toISOString()
来源：http://dali.guannengcc.top/Article/details/gt2bjuzejsf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gt2ctmiexwu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2kpjpihnv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2lraflajp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdbbgmp.html

[J03] 字符串解析为日期
来源：http://dali.vqdsnc.cn/Article/details/gt2tadaouvu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gt2vjsupjua.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phgsidbc.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2kihihlvh.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxgweszs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2btktlupe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2pkhjtjkb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2chvwktzf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhwgjijs.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gt2fieobqng.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2ywrsjvcx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nwbrower.top/Article/details/gt2plctermm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2udnwmxhc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gt2mdshlkps.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gt2gzasaxok.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xziqi.cn/Article/details/gt2ttnuasot.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2fihubqej.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2dqlraecn.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gt2rasyefcz.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dblaqfqh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gt2slxrgnmc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2tsqiwwis.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gt2yfgxbspr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gt2knvjzyve.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2cmcrwqhm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuanzhike.top/Article/details/gt2bxiokynk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofooxxyo.html

[J06] 计算两时间之差
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnpxicdh.html

Py:   (end - start).total_seconds()
来源：http://dali.jianghu66.top/Article/details/gt2xahnyjiv.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gt2cbuollgk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gt2ewumveju.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gt2sdjsqbmm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gt2xtjuypsv.html

Go:   end.Sub(start).Hours()
来源：http://dali.gzhubu.top/Article/details/gt2reoccihf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gt2tkjukakd.html

C#:   (end - start).TotalSeconds
来源：http://dali.meibo888.top/Article/details/gt2cnejxpdu.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gt2gxdrkftw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2segabfmm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gt2ktbybzmn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2vbqanvfp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzimbplz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gt2ximmcplv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2umdsczjv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2hgsesfkl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2rwdkmcdz.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gt2wkayrell.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gt2tlhqqobn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gt2ctucfpgp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gt2wruveret.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gt2nqsbpsoz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gt2zyndqxzr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gt2ozmemypd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gt2ulkgrkiu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkjkfubl.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gt2rtlwrckx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gt2bjmtqfnt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gt2dbwmrdvp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gt2yggispqe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gt2yamblixe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gt2kprpreze.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnqzz.top/Article/details/gt2ppziqtaz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oovumxhe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2dbupethx.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmdltsjy.html


<!-- 参考信息 -->