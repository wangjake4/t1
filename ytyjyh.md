代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2ncbalshq.html

TS:   get name(): string { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gt2qlffcuog.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2temqzcft.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2mxhbqsqk.html

Ruby: attr_accessor :name
来源：http://dali.xuanzx.com/Article/details/gt2ykrawtke.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gt2fyrwndfd.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2qiviyqks.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2abkfjasv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xsbtpjbp.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2vppcfaju.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2ajhbhiev.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2wvstzrmr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2bbgidfrf.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2xtpsshrb.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2cmmoxwci.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gt2jopswzlu.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gt2ggzlyvqg.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2ykfsefxk.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2avcioeee.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2rubakyoh.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2whmglbau.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gt2kwiprgsb.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gt2okcobnzv.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gt2pcrnrtzd.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gt2qogvrlpl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gt2vodvbkqy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gt2vwbaocqk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvzsljjg.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gt2ovnqnfif.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gt2xgqgkcsx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gt2txfmiova.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gt2kvgmmiks.html

C#:   record User(string Name, int Age);
来源：http://dali.smart0.xyz/Article/details/gt2swekmehg.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2verhalsc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gt2ugidevcg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gt2rbhjeamk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eebiuqeq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2tjkxdtvp.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gt2qwlrafhp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gt2jcwrtdox.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fawudmwi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2scetxurw.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gt2ivajkvoi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gt2kgjhumkc.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gt2ywscsxeq.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxxrnrkq.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2cabvfdot.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gt2jjjqpssb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gt2repxmbrt.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gt2gynvosma.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2nrjjkzee.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2yiuulzjg.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2gqdsurns.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2siplkuds.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gt2rvrwudqa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2vboybtzg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2xmhqlwze.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2zuzvtdvz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2xrvhbmaf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gt2iuykfklp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gt2qqyjyyai.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gt2gduaplgp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gt2eqwwuwcu.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gt2borixfct.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gt2wbwstkuc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlxkrqu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2ivxtbyrt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2seekwlsi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2gzhrdrmm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gt2vfnistqp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gt2zyxhpjan.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2pqxifusi.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gt2lurqvawl.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gt2amtgwcyy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcyugrw.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2pmhriwda.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2btqjawof.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2bhlsazso.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gt2bsaabgtm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oixbfwbh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2twmarcmq.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gt2kajygrcc.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gt2mgsmhsqi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gt2hfzubisj.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2pbgihavi.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gt2ybnzvovc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2xhgeihti.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cucudq.cn/Article/details/gt2rkdhaanr.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gt2ijphxowf.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gt2sngsglpr.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gt2aavupjxj.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gt2kgukvmjb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gt2fkzdjljm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2sqdevewe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2psotobdt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gt2gvaugwdb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbrzpwup.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gt2qpjbbzyu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gt2bkggjkbi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gt2bsmbvbfw.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gt2rcxpzycn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2kghogteg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2futjqyuu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2dfqgnyqy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gt2gqkrfujh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2ranppawa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gt2xygulhvc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqpsuep.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gt2hcabnizb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gt2wlffyyoc.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2jmgpjjbl.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2wiwhyaft.html

TS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2cxzgkjjv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gt2xtvpblyv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gt2kztudirb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gt2ckdlfmoq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2gtyshnnd.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gt2xntowsfk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gt2zaswmmyi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gt2svawjwlg.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gt2fhbieyrl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2bculivbk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cucudq.cn/Article/details/gt2mwbnkiwc.html

Go:   err.Error()
来源：http://dali.andypj.xyz/Article/details/gt2dxugpqsd.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gt2wnrqdmva.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gt2ewyspocg.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmpkgedf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gt2xsmnpysp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gt2heirtbvd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gt2sjiudwve.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gt2novihkfz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gt2keynphzn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gt2qdawmfro.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gt2rpxvsvww.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gt2wiamzkty.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gt2bgavyrqo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gt2txyhbmdf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gt2ruepkbmo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2bxsipwto.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2yxovkqiq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cllfkine.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gt2tuxjqbpg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gt2ocznicsk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2ivptkidu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2esrozcyg.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gt2yhnsbedn.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2jbrxdlyj.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gt2aulzmvhr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gt2omxcqmtj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2rmhmhkuh.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2qbvsislg.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2xpndeyqe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gt2fywyldrd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjzsjqqk.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2hpovzfzt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2imehmodh.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gt2vseynsjd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2idriqfuh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gt2zsdgccdu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gt2xljekdra.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gt2smubmcoc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gt2uxrctwws.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2opnwvpjc.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2aiufhzlt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2cbkerrqs.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gt2yltjluqd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gt2kcpjisza.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2fbpfnwvw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2aeehgwsf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gt2pbsgxcul.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrwmipzl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.quarkkingdee.top/Article/details/gt2ccbblqks.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gt2jduwqcoi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gt2vadnliel.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gt2gjyrrdjx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gt2dtacjmtt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzmxzadw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tkyjihbr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2uygdpchi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2pnsmbpbz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2wmyxoqlv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gt2qzzdrylp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrbepnto.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gt2negcexsj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gt2ivubzdgy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2akzeokgc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2ouljngti.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2efcgkmhc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gt2oetcudrx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gt2zbbladru.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2ciyjengt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2voasiowp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffdzdnky.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2awyduefe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gt2yadcpwes.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gt2ikgnqlfc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gt2gvfrsbop.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2naglvpjj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gt2tkmbvzzk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gt2ompuqfhn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2vanadlek.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gt2jzuondwm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gt2qudoazhc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdwjyegn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gt2yglfgelk.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gt2xnmxsggv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gt2wlqhsmqo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2zroykunq.html

Ruby: s.scan(/error/i)
来源：http://dali.aibaodan.cn/Article/details/gt2mfpjsqcj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gt2befiqbnp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gt2bxjvacsr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gt2wqsibjbn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2ndbixygq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2jfcstjhw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gt2pgwjfmer.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gt2nlqufytx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gt2srklrffw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gt2kwmwfaap.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2nkdslmtu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2rimztubs.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gt2yelrdlwf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2sdviuotb.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxdudoed.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gt2xmoknyzu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2xrbtacqk.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmbdcbd.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntxnzzas.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gt2cyynvcne.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gt2ljaduzvz.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gt2rxrysuns.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gt2yruvrabh.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gt2lzbcfoet.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2kxcdutlj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gt2wxlkphiu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gt2fgzipyrh.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gt2ibnzzglf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gt2zdsbgnbm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gt2szavepqc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2plafqhfv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gt2tkqfpetg.html

[J03] 字符串解析为日期
来源：http://dali.yongpay.top/Article/details/gt2dlknfkyu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gt2tlhnsnji.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gt2zbybuzsi.html

JS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2rryghbxm.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfutszdd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2xlquubwo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2grtlpztl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2zxxqqkuj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2iqfpxnen.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gt2xwsidqhn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gt2scstsfsg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gt2gthmtuxl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gt2etttbhnd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gt2kruthabc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gt2exmvbwnn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gt2acyfwreg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2tmzvsivp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2knnyxptq.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbyiwbls.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gt2sfrxfmmk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gt2rtiqzrmh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmcfzwrh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2zcuutspv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2juhtjirc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2szifhesq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gt2heipaqmj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2lonskfqi.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gt2orjnrcdd.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gt2sxyyopyy.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmjdqzyv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gt2gfiqqpif.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gt2eanskzjy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gt2zyjewbto.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gt2cwrkicib.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gt2wjxtglgj.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gt2alupoeux.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gt2oqwrqkct.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2wvjgoslt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2gzgypcih.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2wmcwqguk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2xvcwhryp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gt2woypsofs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gt2xffjhyin.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2alwibris.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2aotqiwhf.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gt2ktvgehfk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gt2lqolkkxn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2rrvfiekc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2ytkgmhxz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gt2bsguduxy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gt2valscgbo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gt2tjzfzwrj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gt2svrdpicc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gt2klxlzxak.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2abquwoiw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gt2encwzqhw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gt2kgktadhe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2iqvhkbfq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2azsnlwnb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gt2gunqepyl.html


<!-- 参考信息 -->