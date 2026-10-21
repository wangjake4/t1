代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtlmzuuqpr.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtgymseuri.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtaacuuivy.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gtelrfmxrv.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihuqakfw.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gteumuvunc.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtdicgrjiu.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gthrdynsrj.html

Java: u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtylldbxyt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtfoihnspl.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthinekzd.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtballhthr.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gtilllwuvf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxyjtunk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gtvlxbuglj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtonacdlen.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gtrpqrqfza.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtfueeegwq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtncscupnd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkgxywgz.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtrjkyomus.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtdfdznxba.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiirwlgtt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhoulong.xyz/Article/details/gtqmdmxthl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gtnlgomdpr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gthgprrzhl.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gtczlxpikd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gtodlpmiuj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gtvisjehqp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gthjfqfimd.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtfuyjrgua.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtzmrutiml.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtmnsbissr.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gthelpajci.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtagkabwoa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtlgydhhya.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gtkerskrjf.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtuogrcvvp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtoblznmrb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcfabihff.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtaemdvnib.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtthibjkwf.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtquublssh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gtevceshdc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtvgflgede.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtnbmkqkfv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtsuuhmxtx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrihngyj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gtcelnvbyo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtwmppplwl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtiijcvmze.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtzwyzpnzj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gtvbzkhctv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtbclfkndy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtsvrkfvok.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtpdrmxshh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtskupkand.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtmsfvftcu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gaohongyu789.top/Article/details/gtavttdqts.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtagdrxspk.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmaejuvbq.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gtyetfmdfd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtddjykjdk.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtyywxykml.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtwliifpzd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtdfsnbmns.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtuibhvdfr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtieadkkht.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtltsfcsxi.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtpnboxhby.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtzgvjeyfu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtaxvqzlun.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtoebpjkmg.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtzeloangy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtsgtlbyau.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtkoodvcew.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtoazbetpl.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtlgaghamm.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtstyphdsr.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvmeydix.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gtmxcjguam.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtethroyzu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtmqextmum.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gthleqscut.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gtscoizbrr.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtdqynqpbg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtaiabsoui.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtulhcuwlf.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtbssqlzkn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtifasgcmu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtpntgdmks.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtgcizzzla.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gtgxkhgkjc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gtigboyimw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtcmcrbzzg.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtadvrtswb.html

[H07] 断言
来源：http://dali.cqqwz.cn/Article/details/gtujgddgvg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gtrmvlgtci.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtewnssfvu.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gttebcuski.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtpawlpdue.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtvlvhpwen.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gtdsvgnadx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gthooistlk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpwjveor.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gtgkhgdrff.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gtqjlepkiq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtipgqzfkt.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gtwuvhlqpg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamqqkvwh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gtaqsbfvhw.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtyxhtqkuo.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gtvwiuajnr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtbdmxcgin.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtcginxskr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtpzarlhan.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gtptqbbtyv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gtjzgpjlwv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cqqwz.cn/Article/details/gtsskxqoaa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzogxkir.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gtcknghodf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gtjbhbturu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtpmmkntub.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtrnjnllcf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtfnesxbna.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtkvtezutk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtapxgaaqs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtyxrjnisy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gtpuulkbhq.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtsacqqgoq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gthejyuhmr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtomjqtpph.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtcgwjipqu.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gtnubhgqia.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthsgkcgbs.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtgmcezvag.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtqzarttui.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtrnuxmsxb.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtuiifntut.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtxznmpylh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gtxqhxunqg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gtizeknish.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtnxevfadm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtgwsmnlyi.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gtcvicjtvz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtbwgpdpmp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtmxqpbvbh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gteygnsrhj.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gtxqxreocz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlgpyqnj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtljugrjzr.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtvlhbbudd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gthxtrvsyh.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gtkispbdxs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gtpvhyrhqw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gtvvakaitm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtwlayzbth.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gtjhadgypf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gtznfgldrc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gttrnyjynw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gtmdmsifre.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtusixnblx.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtzxbtqoqc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gtvwmkuwwi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtsyvhjngh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtapreruln.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtjvmdgypa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtsewtunnc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtcmzmrrhp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gtacafflce.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtfpwtmfbr.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gtdksuiuat.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtbfwxqkto.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gtyqrfuezq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtehudetex.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpahqrnya.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gtrqgpjmgt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtremwnepo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtcgpuawfe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtiddhsghp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gtsrrvzbro.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtgylonzdq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gtbloniiqf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwcxgzii.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtcobdwqks.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtipntmazo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yonumen.top/Article/details/gtzxjzlwmd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtojfvecwh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtjzbidnzj.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gtdfudjcxl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gtooxawywk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtszvrsact.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.andypj.xyz/Article/details/gtelylxgox.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtemaccdne.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtrmijohhf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gtlreylxkn.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgilkynwu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtfohfkjez.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gtxeennfsx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtkmxwgiyh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtkiqsxxul.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtzbxwjwol.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtljspiwin.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtvykobnoj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gtfpeiqund.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gtcqcgnxlh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtyyzhjnhn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvqhphiea.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gtuxjjwibx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxnwbqtqh.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gtcxqhqqoi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gtqbwyexmh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtymesblhf.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtodzbdnla.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gttswbofun.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gtmwtdjosx.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gtujfrtxic.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gtcwvdzdoy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwllraiqr.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtxyytjxza.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtthtmehpw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtfdoczywn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gtrahjbefm.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gtpfszvwsh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtwcgrmvjs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtvcynpwge.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gthbyhomph.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gtfojaennf.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gtleqtuhrh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtdpvneler.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gtaesqoeos.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtlellyfbk.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtoalibtxq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtxlodhmlb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtmoxzuyka.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtcvromvtb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtgsluxknt.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtrfbgauef.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtlfuksglh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gtqyaigugy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gtyknwfcfb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gtrfkwhrff.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gtvrdocnrs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gotoacloud.top/Article/details/gthpizorbv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtmpyjfwwx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gtwbxlmatd.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtgqjbffau.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gtgtuetmcl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhibytzt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtsyhbssns.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtqidgnoxz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtjvsebpmg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtfqxkzrsi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gtqfjdrjly.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gticuirrqz.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndsmqnim.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gtpgqfkcip.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gtkpxqwtyk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gtniiuyrla.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtttjfwidx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gthmuiokol.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gttomdtgtb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gtyvxmmjft.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gtnfbxhbwg.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtfgirkgro.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtdflcmqxk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gttmkrogug.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtxidbmcwv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtgoxmeyli.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtqpxdwtvi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtmucgnetr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtfiopmqbb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtcxzcjecd.html

[J08] 提取年月日与星期
来源：http://dali.jinqigfzy.top/Article/details/gtorshcoig.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gtazqzqlvt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gtlitntfcy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gogol.net.cn/Article/details/gtepeqbkjl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtfjxbfetc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gtrsyfrobv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqrmgszn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gtvvbwyugq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtstppyilg.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gteodbfrro.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtveroiyph.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gtpneepwsz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtsvpxveuj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtbobciuji.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtvwiewpgg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtjirxmtop.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gtcgvsjpgy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gthbgeqgmd.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gtahennyra.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gtmpcbndtx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtulanwubp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gtfznwyefr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gtfwtotloe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gturjdykuj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gtiuopooze.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gtcmljixlb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtwbiifupb.html


<!-- 参考信息 -->