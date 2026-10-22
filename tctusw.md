代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtrclcgnhg.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtzblcxtln.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtsglmvvsu.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gtptfzjlhl.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gtxrixxsro.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtdmullysx.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtkiuclzsi.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtsecfclxg.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtfaefuhep.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtygwuntyr.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtqnxpgqxq.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtxhzafcfj.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gtoavecfyp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrhkbawu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtjpwwfzwv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gtqhqmodfs.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gtlfyaaswo.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtnpapibie.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gtyyfyrnss.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtdwvlyimo.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtcysrkylk.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtptvoggwl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtyqjiupje.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gtdjlexswa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gtzviygeac.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsihlurmp.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtncynhgxn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtjoxmeeos.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gtpwrhkzjx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtzrdihzxd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtadxxodfz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtfgdgqbaa.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtrivfcnbu.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtgunbmlux.html

TS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gteodopeax.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gtbafgkzov.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtzpvaxird.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtggdncxdh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtnafjthfs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtoijcgnyt.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gtraqlbtut.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtiskfhwyw.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtawhddtjd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gtdulhvpot.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtssrkalgc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtvnddqncd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtvjjugrhq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtgdlvxlib.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtxiygdqit.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gthjkfvjaa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtvctrvxjc.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtifjyfxlo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gtsoffadom.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtfynpaykh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdpecxfaz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtyaofyjgj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsegrumvh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhdsrxlz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtxcnczovt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtlbluspwz.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gtrlgchoir.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gtujmahyhz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtkloxhetk.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtqszrjujh.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtevnpwngt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtzqpqiksq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtabwdzrnk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtanhxypof.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtljnmlfjv.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gtwpjhahdb.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gtuwbejrfj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtnsydsffh.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtqmplocxn.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtrjglbunv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtetnqnonf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtcqfglhec.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gtyrvossiw.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtewssizmf.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtwqatgdpk.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtttofwzok.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gtfntapapz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoagxajak.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gttbjngifg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnydhdwik.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtxqdxhvfm.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gtvllahdcn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gttkwoidnd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gtygzyylrb.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gttnnkrbbe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtdkwbejqj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtdymsvrvg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtkqykhvdt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gtpiupzvha.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtcnozwemz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtxcaypeec.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtcudqoerk.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gtqqaroxgo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtnvmzknwn.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiarxtsnp.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtokcsccwn.html

TS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtgdrixeiv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqdxaoro.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtdovuoofj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gteexfbpkw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gteirjwctm.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gteogjqnhf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtyflxktwq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtvsxjlqqv.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtstvvarqm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gtefczjygr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gtlggtkact.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gtwuhjifqr.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtcyojarkc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gtgryvkdmg.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezsuwdgc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gtgkuzttrg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gtooxqcjsw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtvchiimiv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtraovlcih.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxyefapbi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gtyadnrina.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gtdtdzepwg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gtnuncpsll.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtadiyotvt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtnnabqdzk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gtebcckwhd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtyhxcqfuz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtsepjsuvy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gtbxyomwzt.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpeclfgl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtmdhlvllw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtlyjpwrew.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtidzmsqmf.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtuuwqjohz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwcmlsebd.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtamunjjuu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtyiwfinza.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gtchmxqajs.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtpmnketof.html

TS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtfznfxuhh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigufen.top/Article/details/gtrvnqhtcq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuxming.cn/Article/details/gtefzhdsex.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttiftayie.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gtoxibvqec.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gtozayjxnv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgahrkwvy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenzaomai.com/Article/details/gtdolflypy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gtgtgmjsfx.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gtxjdrgdqm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtgiecnrzd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtoptfdplh.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtodohdhmw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gtpcyfvnsf.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtrezqevrc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtnvxwwbzc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtdciuaicy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gtcrdhunlk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gtsvuuverg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtdfgmyxry.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gttyzqexxo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gthihqaqcm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gtxmxtqadk.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gtohfyblvq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jyoumei.cn/Article/details/gtwktqwepj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtfucjvovs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtxpowuwga.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gttxkcwodi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbfgybcn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtyyvvzhas.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gtmqzknigi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtffvszzfq.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gtinayzjja.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gttuqbtwqj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gtwkxphumw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtbynreeyg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwxdbzhc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtuoaxokid.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtuzaklgcu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtvraznfyo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.bjfxy.top/Article/details/gtysvfydbf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gtkpkqosko.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtlvlayxwn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtqjbqheep.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtwpqkshzw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtkmkxoukt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtbxdvtqom.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtzxgvnhow.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gtzxqhlhcp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtxasuxigo.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gtycmvydpb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtldszxeuu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtebbybzdm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gtmjwixgrn.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtcpmqxgwm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gtjrntxirq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxuanxn.top/Article/details/gtnyoadqxc.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gtrpyzaiia.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtmaxpiqjy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gtybtnjqua.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gtrfhlehne.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtvjchnrgq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gttthxnybh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtkmacwypo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtewytvpvo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtfabtsctv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gttvywroni.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtyuydvhhd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqntfqjcn.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gtkjgvmtif.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtfuelsiyn.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gtebgltxoq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtbjidze.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtufbowwwp.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtvikitkxp.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtqtarfkhs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gtitlhipsj.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gtbfblvcda.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gtxbagdzse.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gttupjymub.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtkcoijpph.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtxasugnnu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gttxyhnwyc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gtkrncmbxn.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtgjlnliad.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtheoxigbd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtrkjqhtdo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtwnrvwbbb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gtjpezpgxs.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gthhahserz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwixjuqd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gthhsdppft.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtvdzkglxx.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtlaaguubg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gthjbgdyfj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtnoowyvhs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtsqqesjid.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gtdkusrbxt.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gtcwepgdjh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtdocqjxay.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gthuosgxxi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gtrspmssla.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gtgldsdpok.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtnndnekek.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gthnzwzruu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gtlmhwosep.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtzjzwmboe.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gtzxxwgbvj.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtoxrunazn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gtdcqhlfry.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtidhhrfsz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gttlsvwtdu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtykevgvst.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtcvjyokbf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtbvlfeamp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gzhubu.top/Article/details/gthmbkapvo.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gtvrlhbtlc.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gteqfqrlqr.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gtqtbqcpmz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtpjhtuqhk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtzbhffnhn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gtxecmkybj.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhengqikj.top/Article/details/gtjyahaaej.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gtzcfcxdiz.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtyllrmnph.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbncxrkak.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtvdykhmwy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gtnobjowcx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtikyaezlh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtsflghrhi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gtiruznbrc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gtqsnjptxo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtapvzzutn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtwwthuitv.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtvfkdqclc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrbobyao.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtysafnxik.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gtzvcurlyb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gtitpnsbnz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gtmebvfkat.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gtxgamoklv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gteuatanpt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gtjpblcphs.html

[J09] 时区处理
来源：http://dali.shzxlz.cn/Article/details/gtsgpnqvoy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gtfutdlxln.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yongpay.top/Article/details/gtyobmnoaa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtjezdiobq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gttzhamtes.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gturxwdktn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gtgadrhtuw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtsrscqahj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtkxchazgm.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtcjrlqvhu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtyueshsjg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gtscpmpyah.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtomgqdmgf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsdstymu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gtvkfzkedq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guannengcc.top/Article/details/gtmdcwetkb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtmqhnggnc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtqsbpkume.html


<!-- 参考信息 -->