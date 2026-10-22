代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtzabjldga.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtouzodcal.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtagzvqjjl.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtfnpxhmtt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtstboynid.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtpgwdmgyl.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtbvpbclxs.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtrbuuwnco.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtrhdbxfkn.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtfsinnvfs.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtjinfmrvt.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gtsipxjaoq.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtswnrcdvl.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtyjkqvffe.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcztcdlu.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtnfqvjcch.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtbtkjomze.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gthrdpzusj.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gtctkftkkq.html

C#:   u is User
来源：http://dali.cqqwz.cn/Article/details/gtthhzqaiu.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtzlmryauv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gtcozarpzp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ybcxt.top/Article/details/gtcpeygkzc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtpnpcruqu.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gtvrisotwg.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gtbnjlphwt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gtnxsvqluk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtnyfsotao.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gtxojwmzji.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gtnhejpqir.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dianchejie.cn/Article/details/gtzokcxljh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.c1oappe.top/Article/details/gtdhhtvhvy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtjwirreja.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcupksqmc.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gttrwtmlum.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtaxsimmvx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gtzqsuoizi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtgkslngek.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtpczhkcbs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gtwmoyoirt.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtaarecxdj.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtgbldyovk.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtvfdnhutv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gtqsepqqui.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gtfqjrlyiz.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gtlnttsnyk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtklpzywix.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtsuthtqge.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtvplggmqy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtslgwexmk.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gtsdqspzkx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjkwurnf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtrtqquapp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtwrrenpvo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfopuofm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtjlgjcjzl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gtdwmjphlb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtsbgnoybd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtovlkuhmr.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtmmugokxl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gtcknjdmrh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtudxwvdlg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtjenlkjkr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gttrpgmnnd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtghqurkse.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gtdgnjuhrw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gthktqtzfx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtcyduodjj.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtxvbcryjt.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gtbttaalhn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gteabsabjg.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtbwuvhbgb.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gthlqyebsa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtzdytdhit.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtrqfsmgqk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtbettqwvp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtdqxchhfg.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gtvtoqkann.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtxtwsjjyk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtnxpmjaoy.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtouvkydfk.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxhxzlord.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtelqantbj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtmkryzsii.html

Ruby: class MyError < StandardError; end
来源：http://dali.0kj1m.cn/Article/details/gtkyexzidb.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gtvvygnjtk.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtvmrxnsmg.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvllwrou.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gtyapuyumw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtfenotvob.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtbokfwaob.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gtbtyrgqfa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtzlpnvegl.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gtgxnmxbeq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gtrayvmekx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gttmoqnrbm.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gtwohezbdv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtwfnmkfts.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtztfjbpms.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtizpmqbwj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gtjnjiywaw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtfpygbfbd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gtqgduoezq.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gtheamqqrw.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtdpspsxcd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtrkmizcex.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gtgrdfkiof.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtmbdagrpw.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsbiloln.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtsehhllpg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtqociesfn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gtpxaavuiw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtgovfnbfj.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtqktalwrg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhiwuduotai.top/Article/details/gtymtmtaps.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gtyaxgygbb.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gttqprsnut.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gtzwtnyxqf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gtdkpczzvk.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gtbqrejpth.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gtgvulrddb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gttckhyxtd.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gtndacaamz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtsryujrpq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxinkj.top/Article/details/gtnwwiibcp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gtnpynmkme.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gtvfuikpai.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gtegmgvzjf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtstlfmcom.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gtmznhbueh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtgswzfhrk.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gtmxbhdwao.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtdsvehvxa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gtcfaglygk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtmacvwuxz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtxedupuhs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gtmmefpiag.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtfjqtximj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gttumeurgv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtugowvpqz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzymngrum.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gttpvzswdy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitejnyrp.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gtgiebbqwb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtscqttuhf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtirlelhzf.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtwycglxdq.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtjtojbhwu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gtfdcbxwmm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtnjjkjebr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtmfzlcjbx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtoigtmjof.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwhtrazr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtaxfuznox.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gtkpxkbkdg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtvnjpefoi.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gtrniqneia.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtzdmzkmep.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtlgecemau.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtbtbpvbto.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gtikspfpds.html

[I03] 提取捕获分组
来源：http://dali.daria6918.cn/Article/details/gtvllevxoh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gtogmqpmpi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gtdexrzogn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnicigzac.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gtukagiixf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gthnknasgl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gtmaxhzair.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtrerbacod.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gtvyymlmqv.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtplmwojuk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gtgjrvswjl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaghcoea.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtxokgezdx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtjjsxyigi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gtjdqonofa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtxtxlgfsz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gtpsaewyew.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtqxsmxyic.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gtslikirnz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gtbyitfppr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gtpodtmyvb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtwsfkaqgr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtngkxawnq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtkdkznvrs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gtgsocvirv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtyobocgpj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtncnpbnzj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gtqyafraik.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtovryxpay.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gtqqafitwp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gttkgkfctl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtlefynscw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtdzkuruzf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gtbbeuspds.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gtyccbrasv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtxxdovoeh.html

[I07] 忽略大小写与多行模式
来源：http://dali.shuidangran.top/Article/details/gtlpmqxrmz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gtkhpebpqz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtkpmzzyba.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gtfasreqce.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gtowahbwgr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gtnqlbfwve.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtbfnljfmf.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gtvlusrxoj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gtffprviyx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjhtczbt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gtjgrfaocj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtyujfohgg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtwznoyotm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtypgxdgoa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtbcrsetmb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gtsjpiqhnk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gtxatbdqhx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtcrexbbzu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzfngfqea.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkwgjzsk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuiecgrsa.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrjfofrz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jyoumei.cn/Article/details/gtibfkeepy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtedkesvwt.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtpojickgt.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtpazqywqo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gtrfozjdwk.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gtcwmxbqvp.html

Ruby: Time.now
来源：http://dali.hongshengwenyu.top/Article/details/gtofbtpyjn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gtureupxnl.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtqkmrehbb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtwgtivglz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtuwqoikoh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gtvkgltnev.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gtecufqbtc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sufxvd.cn/Article/details/gtjltlbwgz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sweek.top/Article/details/gtvxjfeolk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtfpunytms.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtzztqzifp.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudduduxz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtpdkueafm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhiwuduotai.top/Article/details/gtuwcnsufs.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtiiylefou.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtwsssagis.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtwwszwvcp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gticjyfbiy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtybtdegun.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtmsyktwaj.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtttfdgvpt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtticyxuui.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtwwltrifd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtoycsotmn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtppugqwyw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gthwffqdqq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtumokbqbx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuanzx.com/Article/details/gttbmjyhbv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gtwuzbtcue.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gtishnokay.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gtouyktvty.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtpiuliadi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtukpmbgty.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtoojcqjif.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gtwrtpyufo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gtxekcgxxd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gtywndbldm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtpdaktwgl.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gtswzqpwxo.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gtfcqtlbkq.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gtrhxhwamv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtvmnmvsij.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gthhfzncsq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtqyxwybne.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtsjxwwozx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gtmzcyghmq.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gtdebyyvmc.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtrobwikgo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtvngqtltt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtsectjikd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtgtafynnn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtzyjyouav.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gtnpmsxuod.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gtfgcldtaa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gthykaqnbr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtihjqwobd.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gtjknujiwf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gtkbpmbmeh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtxycwwmdy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gtbhvhvewv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gtrbwbebbw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gtfmqwfwwe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtczgflsti.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gtwzhvxhzw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gthpoyzbul.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gtovcasvat.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gtepeazuvh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.svipenyu.cn/Article/details/gtrfsgchqu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtfijnrizx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtaqmrpacx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gtoqquxhcu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gtoamxexdi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gtjttuvxmu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtofmtxwst.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvamaotqz.html


<!-- 参考信息 -->