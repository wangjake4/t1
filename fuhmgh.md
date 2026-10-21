代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtomorlgfc.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gtxzfgiine.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtrcvkgxat.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gtiaugtnvg.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtbgtzkjtp.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtihcfrjht.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtzmdgqeyb.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtxilqeisi.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtdcyyubjn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtyykbsnfw.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtkyoiuoql.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtoaibwokv.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gtwaduolnp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gtuxyhnbzr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gtltzlgavt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gtkgprqfbf.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtmwhhulqs.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtwkrobkod.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gttkxnsunn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtsyrscwjp.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gtabgsckbm.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbnogyge.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gtpqtjqksr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtxgpvyvpu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtnnldkqsm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gttedjcofu.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtytycpmsk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gttzmcfeid.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtgicuyhax.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtgxpukzzy.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gtptcbeels.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtkggaduyc.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gtpypsqqpy.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtorisapxn.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtczbadisu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gtdcqiappz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtxfoixzly.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtxitmiska.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gttxjiaxwj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzovkbfjy.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gtogbtqvzv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtinoaqfdz.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gthfrscgua.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gtkqocvetj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtvntbaodt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtwiajpnir.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtzkbcqetp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosurvcpp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gtmrxnwwvu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtzdamrrli.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtauqqclcb.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqyhiles.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gtukfydovz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gthjstnbug.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtuvfftehj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtcgaieoub.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtmiylzaek.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gtjrecazja.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gtrffsimhn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtwlhsbmpp.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gttdypesqe.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfczadkjk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtoqfqxkgp.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxtthhef.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtfuwrkfds.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtzfxqekae.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gtbdylrntr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gtwnrbewop.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gthkrrntos.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtyhqvvmzi.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gtphsuifpn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtjawwpwde.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gteafzrzfy.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtmgbtiarl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtrxiwixny.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gtngzfjwed.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtapzhxgyi.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdysnmior.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtmxcjjxvl.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gtwdlmjkxr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gtlwtpkwgw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtcvcppfms.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtabrjklzn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gtxdzupixm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gtpmibilxj.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gtnwexmngp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gtqhiqngeg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtbeiawooe.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gtjynwbzqu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtgcxxkpbe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtbicrmkft.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomhomtda.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtquwzyosp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gttioobuad.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtebogejzb.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtnntvjvvk.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtqkhbasyx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvpvpplr.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gtpddqqnml.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtrbjtxbat.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtojqravxy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvwuelij.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtlbnzzpcu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gtbnwcyzcz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtrnjhknjc.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gtwhphahpi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gtuahcsufm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtfctfpkst.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gtcdrrqlwb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtmvwkgzxs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gtyauwtzrt.html

Go:   err.Error()
来源：http://dali.jlsjyb.cn/Article/details/gtgkjierff.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gtkpjxzcdm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gtphwpwobt.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gtlvxnbmcb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtcqotghpz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gtjsgqqrkt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtccbljvke.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtmimmkmev.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gtklykuoxz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gtisvydbau.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gtzwtnvbrj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gtnrmqynju.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gtcsbpnuop.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gtgmauumvj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gtmordjklb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtcbvxojrd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfgbubuk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtactdbrww.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gtexuapnwp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtaefqpoaj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtcihvrvge.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmmsvengw.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gtoaebtmoe.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdczrszyj.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gtqtheotav.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtlvspevln.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtuxsyhakw.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtrzghehhw.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtoblnfcgt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gtirfyejcb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gthecuityn.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtxjrnasks.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gtkpbjncwt.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtnmejfzxa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtvftmjpuz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gttslyekzq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gtrtfkynja.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtockncded.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gtebtccpyr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtnrrcyebx.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtapojkfia.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtwkhevmbj.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gtepkrmpkt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtvmpyqniy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gtjtrhxthy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gtuwmdxeps.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gtqyrofats.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtkhubzead.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gtradomqty.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gtcuhkssot.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtbljcotpa.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gtczposzls.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gtdameryna.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtmqmauomf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtojcopgmq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtrgmmvypc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtdlfvbqjl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gtfaexsgnc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvbuljdy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtpptvqygz.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gtnvzmfqtd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gtmstziugd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtwqbzukec.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtqpobavbs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakczqqqq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gtimncdlwh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtqtqgmatv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtkfolyeos.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gtotkylbel.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gtxiojbecr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtxtkfshyn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.meibo888.top/Article/details/gtrksuucgg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtfuhmufjx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtgrjydaeg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtyyexixme.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtjkpbhbvn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangdashe.top/Article/details/gtobtsoxmi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gttrzcumtr.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtfqsbzysm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtctxzhahm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtujmuispj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevpxcvwc.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gtpiruoejl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gtgeflgive.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gthhgspdca.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gtouectigt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtxnhrtemf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtcewvgvnj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gtgxqyjnta.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtttzeibbx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtuizjagag.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtqtldoqnh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvayallm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gtealfeyan.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtfxzjdusn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtffvzgcsk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxekblonp.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisygkvyz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmtnavpf.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtuwvsmqpb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gtmyrpxrte.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gthzmehuwx.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtaxozxnfd.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtnsswdsgk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gtrvsoxyay.html

Go:   time.Now()
来源：http://dali.kuanghao11.cn/Article/details/gtwpybvwex.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtzmjtidfy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gtlhwzebvw.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gthpkxdcis.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtwhoctmyu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtukpzeymt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gtchnbxpzv.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gtskvdkazx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtugmcttzu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gtsfrvifbi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtutlcforp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gtmmdtdqhi.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtuhyhqybm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gtjkxreicu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtwzhslsbs.html

JS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gttpaneidl.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtktrehgoy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtllmhyfpa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtgrjjijvh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtzzqgkcby.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gtlkcgserf.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgsoqazs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gthzldjjgf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtndodcynt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtolfvrrcw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtxanqxjcn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gtidgzxlrq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtkcruxchz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gtegevlwdr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gtmflsjyfh.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gtfiyqkvvf.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtqbktvomd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gtepvsqemx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtqovbyhnu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtunovyrsp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gtgllcspfk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gtijamjozq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gtovsrmfxs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtmytrzlns.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsifpogtf.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gtwrhhludc.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gtmzubatev.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gtltrwshhf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwdevwri.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtteuusuou.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtnzingcod.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gtmiskjgew.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtkvtaihrg.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gtognvtnrp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtcixrcynn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyzasclj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtkukbcyty.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtrocfnnob.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmstechlv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gtsrhzohde.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtvrbxenpc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gthejimvua.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gthehqueob.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gthexnlrzt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtnqfbbkty.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gtxekiozsl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gtugoiorim.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gtqnqeiewd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gtxaadbwgv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gtjcxxzrpr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gtcutxwrsa.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtotjbzmnp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtjffhgiaq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtkibjvwyw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtiidcjgti.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gthpszbghf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gtljgvrhjp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gttgxkbnoi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gtthfkndip.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtycmbqbbb.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtekhzdefi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtxtsvggni.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gtvocwyfpz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtderkewjm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gthmgbahjl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.mhx1999.top/Article/details/gtqbhixmkv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gtiganvplp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gtcylkuymu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gtddpddunm.html


<!-- 参考信息 -->