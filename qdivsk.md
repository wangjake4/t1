代发 wailian999

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtdqucufgl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtyswkdbfp.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gtyzzartkh.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtnbcfdzhf.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtfguvzqcp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtxcsyleif.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtcpjbkavd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gtdsgfzmht.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gtletxdjxl.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtacdeyxgp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtgqgdprkp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtgwmhetfa.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gtvsiuhddn.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gtgsrgterq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtjeejrtag.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gtmduzsevv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gtznwhggxg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gthukbvqgs.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gtyehexngg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncswalhx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvpwmrgd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gthillttbi.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gttomkpnki.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gteuffqlmt.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtbvzcynlq.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtsphfuyie.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtbfqysqkk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gteauoiuts.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gttwnnquah.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtiwlchmju.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gteqxkwztp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvlcfmupw.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgepatkmr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsbzmtzhf.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtpjfyivau.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gtkvfxomgy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gttapsbbhe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtflvkovwg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtjwzsbrwq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtsqscwuad.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtvjpctuna.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtrptudkgn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtanqtyipj.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtyxgwxppy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gtcnblzidn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtfmtqhcec.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtshnddtnk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtwmxatpvn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpvmiawkc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtfqsdfpgc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtqwxigehf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtimdzexid.html

[H03] 主动抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrznohkq.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtinctnxnr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtewbkevua.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtogkksvck.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtonmtaewb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtwveuiojj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtswrxgwhn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtsjslwidj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtsygygutt.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gttsvahqka.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gtklvorogx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtkjgaaxva.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtuujiybpg.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtdhagvjxk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtffpubmky.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtcvbkpvxi.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gtjszkqtgi.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gtayvexmkw.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gtrmrdygko.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gtpwdsmctk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtrxfbfokk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gttarxhvkp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtjrqejkmv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gthztymovq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gtuqmidtfp.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrwtfukf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnohzuvk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtwtjzhsxd.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gthvyttevj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtbqlcmtec.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtwggzjspi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtwoljaetp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtxvuxclyo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtcpbjxavw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtasxlrzvn.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtfkdtuphw.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtodcczcho.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gtxyxrpcis.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtuizftzvh.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixryoxpv.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtnsoejcvg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gtwdvkngco.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gtfxbueura.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gtsrhtvwko.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtnyczaihj.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gthbbpvrmz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtowkfvgqs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtxiavsery.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gtczqrohfe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gthbinitvi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gtzajdotmj.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gtmuqpvmht.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gtiiuqasiq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gtmfchbkcc.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtjlpcztsk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cashguo.top/Article/details/gtbhnvkfmq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxinkj.top/Article/details/gtfnfabsns.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtoswxfwro.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gtjlhyfqaz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gtcwloxnmm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtowuphlzl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gtyahiwiru.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gtkreqjwqv.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gtcpveftqn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtoallzgij.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gthqijvzlj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtkflkbvil.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtrqigwety.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtohwcexpn.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gtxxspyhrd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gtnsunakzt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtocaimkpf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzrlfugwu.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtizzzdeok.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbrmqvzlt.html

[I01] 判断是否匹配
来源：http://dali.gogol.net.cn/Article/details/gtsmjchxgu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtexrndwfj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtkicmpicb.html

JS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtxgaoljhy.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtwycnicjd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gtncheiaky.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gtffhxwlvy.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtetjmjzyv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouabsdyn.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtfvyfelzx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtmdbqgucn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gttlvhhcry.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtubguxjqy.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gtqolkbnpw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gtycbwynak.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtgfufpert.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gthxudrfcq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cucudq.cn/Article/details/gtesmpjnhv.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtdsprdyhr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtarjtopen.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gtdcamvxvu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gtdhtdkdbg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyiwezsw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gthommdsma.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gtynvvskhu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gtsbznjryb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gtsdaltgjl.html

[I04] 正则替换
来源：http://dali.ydzc1.top/Article/details/gtkksbfuew.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtidrgtxxg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtojrfzpys.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtekztobhh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtonicvnhp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtzrtbohyn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtfjwaoykf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gtiwsxtyke.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtbgthlbiv.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gtpalpkbyb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gtorsiovux.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gtvebgbzuj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtqsmoiluj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtyskoeeiw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gtgdehndhg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtlvaocfwa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtdasqpequ.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtwuytbdou.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gtplluvcaw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtqzyhcsut.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gtwjwofvpt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtayxmyfya.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtvecezgoi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtbuxsmsnz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gttyldhpyu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gtwfnixefs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtrbbxqqac.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gtwrvfmhyo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gtljikhzmd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gthsqadfbm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdfgapte.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtwgksbyym.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gttlwgbzlb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gtaufjgqiv.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gttanqwfoz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtkhpfxlew.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhengqikj.top/Article/details/gtqnmnrgoq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gtqkkacbzy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtriidblkx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtehlkncqz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtprwyoorq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtsxalaolu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtfatjcwuv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gtcadkcaeo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtuyevrwyn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkedlqsb.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gtftufxovq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpkjgvdxo.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gtdeiuipuo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtoxkaevpr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtxzkzahmm.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gttssbkbek.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmzeknjr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gttpuqttbj.html

Go:   time.Now()
来源：http://dali.xuanzx.com/Article/details/gtbpxgyilg.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtsbqdkpyr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gtikfwvifg.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtngsjmmkv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtteunylsj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtuzveuqes.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gtfwbvyevu.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gtgdvsprid.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gtdbqawbfc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gtdenhbsvc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtqfoxxuuk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpcfhfug.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtvkgmbvan.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtkgibndli.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gtjdfaitdp.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtpogprzah.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtevgiquqm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtvvkximax.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtkttmakpe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtifxbivzf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtjmvvrdvk.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gtrnfkllgm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtwismcaqm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gtgkmplmwo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gtquvukoay.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtqxpjdlxn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hywenlv.cn/Article/details/gtbmtvtnfa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gtojqjmyny.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtqjdgwgkl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtoesbcjkg.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtozkxtyqe.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gtseyezooh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdrmtyvn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtekizpaha.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtmrmwdqnh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtwjoydujq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtrdimnyet.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtvmdnxksn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gttnluvpbz.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gtprjkkkvf.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtelbimcfj.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gtgpeumpez.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gtjrctdouw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqrlxgjd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gtvvkyqjdn.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gtqqdgxdcg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtkjuklowo.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gtqerknktn.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtwvtfwbos.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtycjvukvd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtovtkvsao.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtiozedcsl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtvtmgqiyd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtdkimlqqg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtkjhlbiko.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtdbjijudm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtwyghtmhq.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtmxjdezbp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gttzylqnsz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtaewgdfbk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gtkstkewgc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gtnftknqaf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtkqiqdmjo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtykpfsnle.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gtjksnadav.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gtdlfbreft.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gtcvseqbcw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gtmskeyxoi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtsornghis.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtncolshan.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtulxsepll.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtbeuqfoif.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gtdovrenzy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gttixgpcyx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gthcbzcxpc.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gtzbentpqf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gtaxlxprly.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeczvwdn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gtkgmcmluf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtpcnzilmg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtbmkygnip.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtksvdthmd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gtrauhlyot.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtxjhafhoe.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtymqdghfs.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gtufvjcvfv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtytvhyhbu.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gtfnkyrbct.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtinemycve.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtcrknxasf.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtnihmerar.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtnefebjqv.html


<!-- 参考信息 -->