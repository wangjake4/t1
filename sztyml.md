代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gtllodxfzw.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtfaykkukk.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gtnpwrpzly.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzkdkgno.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtitnhnjgu.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtclvfdcxp.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtkgdmngww.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtumiilvzo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtjlivsqei.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtxewjctne.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtjfoxjcni.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtjklxdcjk.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtrtcgpjic.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtvuevwprb.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtofabyqgc.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtyyxrfwgb.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtablqcact.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gtmyocheef.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtjdawbftu.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtmlrzyhnx.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtizbecagw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gtiikocuvi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtkngzbuoq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtrmquejhg.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtsjyujtfo.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtxmtayllx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtiqovmgkr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoepgjvc.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtymqcsrjt.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtrybtacyy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtvvyodryj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtgfogjnxl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtcogpbnvz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtxpgjwwcb.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gteyjddkoy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtrilsjnqb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gtmdkhlpqt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gthuqzhszy.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwdchvmm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtkhmeczxc.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtsubthrqx.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gttqtdapcl.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtayfsdeke.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gtbjbfaujv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gthppcyjsn.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gtwsaqctkr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtsatoklea.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvaivmetg.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gtycyrhrbe.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpirwopjc.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtviflamqe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtzomgadlc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxbzhrwoc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtyltbefyy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtluaxhral.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gtygbndobh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtwuhdtiof.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtloqdlaik.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtuzymkazt.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gtgbuusdky.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gtzcybtexb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtdtucdxeu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtlebwjtxp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemdmshmz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtowhyykae.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtwnyuoxgg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gtjeaufyic.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtdrzlplik.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtvnkemdsu.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gtdmjaaogk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtwcctkaps.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtwmhpowvg.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gteqfpqoly.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtpqvoxnlb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gtrrvazzas.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtshklpfxt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtoifmikdz.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtqwhtutfh.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gtcbnlqczj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtihygcdkv.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtkhfoweeb.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtjugiflkz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtflkcluhx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gtfghlydnq.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gthcujthcb.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gthsixhlig.html

[H05] 捕获特定类型
来源：http://dali.ehwqpu.com/Article/details/gtrxitomvu.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtdoztcgqs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtwyaxomfm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtdwmnptee.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtbggactic.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gtmmmpjwrm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtkhiydyxc.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtepoagfrr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtbgxkalym.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gtkyhmlksg.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtjvsvxmoe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gttdglmjho.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhpuichq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtvpraplde.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbsinqqw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gthbkltewo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gtbjikpqpw.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtaxmzbhhp.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gtchiddiao.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gtmdzuppqa.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gtwzutkerb.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtinhvqqni.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtiygmelxt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtvzfsgspw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gthhqvgqfb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtppvnzuzx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmqouroq.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtasgggh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gtagrpybsf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtyorqvied.html

JS:   e.message;  e.stack
来源：http://dali.jiagoushi.top/Article/details/gtxfmvtfsc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtyvghokrm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gtbcdzcmmf.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtgtscub.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gtdprfehgl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtfzfhyhgh.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtbzzwnnal.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gtttrwmhcf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtsjgbjxpk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtwkbfcnen.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gtlmiuvpcj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtkcsuxwns.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlogvobdf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtruhxennw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gtjtbsvdqi.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gtrxslpjdq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gtihjczavv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gtfxjpyjmp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtfcfrgbcr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtqkhondmx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gtajmilyeh.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtjnivaqxn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gtmhosxwgh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtzcspazgp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtiunccnqe.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtmeefeolk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpeoubpsl.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtjipciwjz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtczfqqwup.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtxcykqnpt.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gteirvpbql.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gthxtxcrch.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gtscddvxmr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gticfxsvlh.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtvfuzslue.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gthycsbqxm.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gttvtmtztb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtkxokljoq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtwwpfchan.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cdnleiting.top/Article/details/gtmajwrnvb.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gthqqlfkvr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmvgudud.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtqyfynrgq.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtymmfkszu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtmlgwynca.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gtsupxhwey.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gtlzoaxzfd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtilobqsew.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gtuzhmbffn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gtgcuzcewj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtmqenejvu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gtazwjclaa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gotoacloud.top/Article/details/gtqbfwsuyo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtvsffxtgo.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gteohenesp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gtuhwplpxx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtahyyywsf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtezklvoor.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtqheqjcts.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtocttkkzp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweejuomo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtymyhevti.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfkouzmw.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtrhdbhyng.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tanke756.top/Article/details/gttwdmekfr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gttvhpahxr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtvsddhbzs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtmuizvjep.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtmtokxiyw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtrcfhnesg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtgpjtnemw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtsmlqylfm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gtaqskheba.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtvmlaxwmh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gtzebpegyk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtaerwydcs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtvjipgpjy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtyiapyjdm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gtsuvuhbcm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtbkawsane.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtveypblum.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtpixseqou.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gttingbvzy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtbcfrbuol.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gtatpcjppn.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gtqagylrvq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuscocil.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtcmjfxhje.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gtpbstjmzw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guowangkeji.top/Article/details/gtnraihtlk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtqyirfspm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtqzvsmcsh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtukwyioda.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtdfkqlebb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtqezzjjoy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglwkeefz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gtasrvzbol.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gtlxvuckfv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtmagaleev.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtsbkteonh.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtuwgrtkxd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgewfsthg.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gtrtgpupvc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hongshengwenyu.top/Article/details/gtuhjrrbdi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtcafuficp.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtegijqaso.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtbuneqkww.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gtzpopnfeh.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gtqwcynteg.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtngsswyzl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtivicejth.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtnhvljiam.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtiqpstnex.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtnyitytrp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtmladdezz.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gtdyjgsqdw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtdvtcjkdr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gtvjpcfeki.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtpvlskvqx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gtgwxjeezh.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gtoyntvdct.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtdfsiqhvq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtxifswohf.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtupzfikhd.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtncenxcrp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtztdcznla.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtpnfcnjeg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtdzvbkoff.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.redwolf501.top/Article/details/gtviljccxe.html

[J04] 时间戳与日期互转
来源：http://dali.zhoulong.xyz/Article/details/gtgktfivyl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gtqgyydwts.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zdqjudy.top/Article/details/gtplwvpisg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtnqvxqqfu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtfbhdiisp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gtpztolajc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gtgeayaxyl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gtucdeqvjo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gtzocqyzfy.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxnfzgqd.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gtbmktipgu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgfzy.top/Article/details/gtfirvdazi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtuamehhcc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtkakwezhc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gthxrbsubo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtkcjyixwy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtxqdegnnh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gtcnrzsbuf.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxlgzvwi.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gtswbotyey.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gtelcqouum.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtqfhsfagc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gtfxrcjcqy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gtwukltokk.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtwvatcjwz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yueranfly.top/Article/details/gtdhlpkwrt.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gtwnnfrhcf.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gtxfegooho.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtrljprtis.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjelpwqqa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtsjljullx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtocvcawoh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoojhtkjx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtphbfpnmu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtjvasarel.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtksrznhwd.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gtyvijzpxu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gtxvpshaag.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gttdobtsya.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gtgmlwdpkj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gtnbqhoact.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gthrusuphl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgfpkdnc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsmsrqkl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gtuwfppdsl.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtaieotmal.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gtjydlnwdw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gtfzmwskrm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtrjolhzix.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtmsdioqsk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gtlvgfclol.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gttxbjjzpf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtbaaupyzi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gtmdfztnae.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gtyrtqbrjf.html


<!-- 参考信息 -->