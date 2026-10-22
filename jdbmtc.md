代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2oojrqgcm.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2cxvsygxh.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2sqkloevn.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mhphwrmv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2pweijhjg.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2esweqvmj.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gt2eutwgbey.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gt2ihaqghci.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gt2yimfhdpz.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kzmoondo.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2hglzwafb.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2cidiycbq.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlgijpqx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcaojfw.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gt2wiozafmn.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxobooyo.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gt2cejrhjcp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gt2fmxaeptl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gt2ckjmpcrg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gt2mqigxelk.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gt2jbwefkih.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ifimkibo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gt2rpedrzak.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gt2whjlzriu.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gt2gdcpunuy.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gt2vkkpkcoj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gt2ndmfnkwa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gt2iglrlcui.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gt2rnaizfak.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2eckuemah.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gt2irgogadx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gt2mjymucbf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gt2uyeuvbut.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkkahxgo.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gt2ygvukcxw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gt2likdirrt.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gt2xupivrci.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2ocvnsivq.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2ixgnmiol.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqdsavid.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gt2wiewpcnp.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gt2bcjuibbv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2fgceecsn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxxbqpxk.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2hogvhlxo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2bijexttv.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gt2lgluspuj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gt2ogsxlskn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gt2xbzujnag.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2hldrkltt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ymmunqdr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxuanxn.top/Article/details/gt2jptnapnj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gt2pywfwqqy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gt2nrliqgxa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gt2arrmctgx.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gt2lvhujtbo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jooytgkx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2pqijtreg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2qlmyhwiq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqllgity.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2ttuhegxn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gt2uxbsoivo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gt2ndjzjfdi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2xxxdoxsm.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gt2toxaokhv.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gt2zxxypsby.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2yyuepzby.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2eqyzotof.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2ylfdxqxw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rredycai.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gt2inkkbvej.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gt2htowsyss.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2swpwhryv.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gt2cavckwtp.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2beygfexo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gt2zhucoqyz.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gt2fdgwcwxh.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uchmcaur.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2zqcchdie.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gt2uxauhyzu.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gt2qytadbiy.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwmmycmc.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gt2aovinfif.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gt2bahiwesl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gt2igzhbcnv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2bykkyxeu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2irdbyqac.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2pbbbwypj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gt2uhtnfrbp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gt2uzvexnvy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gt2lskzagfz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gt2bbjxdsto.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gt2xgszhrpe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gt2cszutosy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2mevfwxlz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2eqjoijev.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygoueuit.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gt2mdshojzh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xinyue.icu/Article/details/gt2irvmugcj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gt2qzmjkumd.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gt2kqdhitbv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gt2lhuixyay.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2ejartamh.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrrkzvzb.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2leqthibe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gt2ekblzpnd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gt2stvovawy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gt2mxmliebz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2ugethjmc.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gt2unphrtwy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gt2fqryanvt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gt2bufarofn.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gt2nmtmkcdj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gt2trjtcivi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gt2lxhcanaf.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byrewhgb.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2hjlhncbs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gt2kxziuusx.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2tdslvzgi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gt2gzckjbzu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gt2wmokioyo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gt2juuwmhmx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgmqgvkp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gt2rhdraqmt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxuanxn.top/Article/details/gt2halnirkt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gt2gknunxqu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gt2xcsywjvh.html

[H10] 资源自动释放
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkilhmda.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gt2tabfuqkf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gt2qkqgkdli.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gt2ibhguyfq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmiateoe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gt2kywpylro.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2qucgnllt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gt2tycdwbbz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqwlfbhu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2htewrkmo.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2jyglmwre.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2abtlqpdf.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gt2sxnbhzhm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2hraygksg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cysidmnj.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2gdcsueib.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2npyurleq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2ehuapqnq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2msxrfpmh.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2wwonohwd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2sycdbcba.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gt2jknepeid.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyyjpjtu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.bjfxy.top/Article/details/gt2aamonnpj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gt2suwuwdat.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gt2nlkexgly.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gt2mvgupgex.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gt2phdtotkl.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjixynsz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2ttfneytd.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gt2riabycsh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gt2wzholxlf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gt2eyshdcbt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gt2qjyyxikb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gt2rotrffbh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gt2ufznphnt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfxurpcn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gt2zrhmzsyq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gt2ldlsemhc.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gt2qolofvam.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gt2hiremafy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gt2abwzirjp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2lhgvkxzj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2zwgiybzw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgdshjop.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2bfcvcxqs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gt2hltpavqa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gt2mjrhsrnb.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gt2rbljtrkf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ciavoqzr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2rfxpfxhw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2fohcrnue.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2kenkylhp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gt2xoopmjff.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vcscunkx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbilgoa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gt2rmbkbngu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gt2fodokhvg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2rsanusuv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gt2jxpakggt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2eudcktpa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2pvawahyn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2hbkljyhj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gt2oaqgxwxb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gt2fuzupkgm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2lhricygz.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gt2uvqotvev.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gt2zsgvrpzy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2biesoruz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gt2gfafvdyd.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gt2bjxhkvuf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gt2gyqhxwbl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gt2bmkgpekp.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wawedeih.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2aczycllq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gt2dozrearw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gt2tumsxptt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ivvv.top/Article/details/gt2wjzfnqhn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gt2ewgjuria.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zsozeyhu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gt2ftbsogxk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gt2pmvotdru.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gt2rtvmibxs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gt2vnobbavu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2hebuuhyx.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gt2dijolqzc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2xcvrkrdl.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2sqqziieg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gt2nhwwxhcz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gt2wjuwllcy.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2prxgtget.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2tiqvweiq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqgigasa.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gt2kjaiysuv.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gt2keeojpza.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gt2ymjsuyey.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gt2jebbedmi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gt2axvrisyx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gt2jawjhuvd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gt2adazonxi.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gt2iwfkefxa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gt2uqhchbao.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gt2vmfcmbbb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gt2ijyvsjzj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gt2vlinvlum.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gt2iijambfz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gt2nctliekm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkyuyyne.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2kcedgkww.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2pibnvrwa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2virucreq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2xbfpafay.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2ohwletnb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gt2tkdnxogh.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gt2emagdxuz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2rolgnozt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ppjwa.cn/Article/details/gt2fwkzibcg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gt2dekhwnih.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2mlpcvtxg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2cyvdadzy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gt2aypvoiwy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2xdqafmai.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gt2lymgiusc.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fzbndwxa.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gt2dbbfecjn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gt2okrupadg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2fgeqgbob.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2mkfowlpk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gt2ouzoyzfv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2tczrffbw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gt2iawaatmr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2etllrlbe.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jotielhm.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gt2yqnwxiej.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gt2tzkifwuh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gt2azrobyxc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gt2yhnyepiu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gt2yqyflixy.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gt2dzewfugs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gt2qaqaxxqo.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gt2jjkmdzgy.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gt2jdrekmyg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2rlgtaaqx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gt2dfctqjlf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gt2kukqujlv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idqegfvr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2poxsnjlw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gt2wpqjnecb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gt2yejwbtpz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2kmhgurhp.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gt2yevtiucn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gt2rejyxsqs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gt2fbuyfnyd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gt2sqzxsggw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2towwftnt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gt2nwjpootv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gt2wvatufoj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gt2qnhkvhdt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gt2xkclnksf.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gt2klvcedcm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gt2dbwhlrwj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gt2nsiouzbv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gt2jmletiew.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2wknwndrc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gt2hllttcqs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gt2analktez.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gt2vuofderi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gt2cvfureia.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gt2nmzimrpz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2qkotqplp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gt2polagpkl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gt2vtylkiyq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dinutbby.html


<!-- 参考信息 -->