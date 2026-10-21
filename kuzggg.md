代发 wailian999

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gtngzyzkxj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gtlwbnnffm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtzddwgbsk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtmbuemwwg.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gttvzrmdau.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gtyaexampj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthaqldpiw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtdbwrhysa.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtndloxbhs.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtvniyineu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gtnfhyqwma.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtgjodbvey.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtfdsrsanj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtluqfxknk.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtenxqtgfx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtrgrugxnf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtkujmomlc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtrkvmxxqb.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtcffqdtww.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtuxcbomig.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtrgqnegfp.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtkphfqdpc.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtmyblwnoy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gtlfnjjufq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtrklbtgvl.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gtyoqqtrre.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtpgpgsipk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfcxktdv.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gtfdkbeojt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtktxsthet.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtmofxmwdo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gtrjhentgv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtsmswceeq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtfznsqmhr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtejizklfv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gtdxvrephv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gterengxcf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtvzwewjfb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnwhzoqt.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gtqgrqquuu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gtektfbsig.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtjzhcepmp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtgsmjlybr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtvkkgovue.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbhnaepm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtkoyofzxx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gtaxwwgrcu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtrvszoigv.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtshxodcso.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gtmhxkjoqo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtremfgqgh.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtvlhawvyq.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtcrlqrexx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gttgosevml.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gtfzgopmuf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gteypnosvh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtmvqosiwd.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gtaleymyre.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtamozvdmg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtovpsmofc.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtulqxnnsw.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtevliegyn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gtikydduqf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtggdavdek.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gteawmiior.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gthhsoimop.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcllfmcjq.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gthkomeaon.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtzrltzyty.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtixhfdhnt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtaryafyvt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtbkcnerky.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtityixish.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtwcvbjbdk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gtfyfhbltf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gtzuijrhse.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtolxpwdox.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gthyinjxke.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtxifmlrxq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtqwmoedro.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gtoakvlmab.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gtcndtwnld.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtimelwdjf.html

C#:   obj?.A?.B ?? default
来源：http://dali.cucudq.cn/Article/details/gtrwlqcopq.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtnplsjbpq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtzuybqxuq.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnosspivt.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtecnvbyvl.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtdqswphgk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtdouoytck.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gtadxcjbdo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gthtnaxefp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtgmknjmbg.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gtqujnlvtp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gttpaoeild.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtrpbkoybz.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtciwdkqss.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtmqoqmhjy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gtjzutzhgt.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gtrokkuklk.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtlzzlybbs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gtggawwjtp.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtyczxddbz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gtryxjjpza.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkvehobo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtybaveapb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfythpppn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gthpnsnlsf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gtzpgdpnjx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gtyoiqdoyi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gtrwofdvzl.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtxcisehwe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtkdnhprxg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtqjawhkgh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtbwlbifpf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gthyshravy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtcljdjxqk.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gtdtrziorw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtbvshxram.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtqhwiaeal.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtuuzbxojy.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtmtmskqzj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbuaiqoav.html

[I01] 判断是否匹配
来源：http://dali.hnxiangtu.top/Article/details/gtvdprztvm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtqoomcefk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwbsibvw.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtvlcnrkzf.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtxjljewgy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtytwyimen.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gtfgfqrfsv.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtiwmkunkk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gteszryhvd.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtppyiztgt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtsclkurxm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gtlmfiyasx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtecdbwqvp.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gtjkdipbiq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjeknnpy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhafasxq.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtjwibhotc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gtgnkxxhrc.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoenwsxzu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.vqdsnc.cn/Article/details/gtxnwucvsm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gtovpclfmv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gtyhogxdis.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtjpiegtde.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gtwpljookb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gtvmnumjsj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gtckfiwooe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gthfljegqh.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtdsehmlgl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gtzudoayjq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gtdeugshsb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtwjatmxmv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtaltkeiii.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtajgvsnkv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gtnullarku.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gtnxvlybhl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtzhzxlbdg.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtqaqvuvfh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gtiunwnegd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gtbdoisumj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtaqenwfbj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhqcxsbu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gtiupyhxfa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtiobkglso.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmkjcjfg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcoxnmhxu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gtpzqpdreq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtujsbwqbk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gtxiyuduic.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrgydsbv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtefsysfqn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtgajexxsa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cqqwz.cn/Article/details/gtpuqvfzqy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gttfhgyaoq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtgoxcyvdv.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gteghkiihe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gtkhtisbjk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtsxnzharz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtybsutyqm.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gtrobepthg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtqvidrwwy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gtlqoleweq.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtfbaimpcn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gtuojwigzn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtkkepgdkm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gtbnkqqlcz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjohijsmn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtfqvvhazk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gthwbazbop.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtlgovmrve.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gttlhqxnql.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gtazvwsnzk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtvrhkdevh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqshjngww.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtldfuwkrh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxpyfcjhg.html

[J01] 获取当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtsnwrppwh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gtdekvifqn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtqboiewaz.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtdbejdydl.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtihmomqkc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gtydwwzodw.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtpkhckzec.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gtwrlyvvfa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daxiang520.top/Article/details/gtxjbuscqi.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gtfzbiqytx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtbaizzrqf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtqkwmcuej.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gteyzmcmab.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gtfkqpecgk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtnxpqjpxa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtwplbreea.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtkamchbws.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gtqoyqdian.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtsotpzybi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gtvacthxlm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtrgpohyra.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtoyczyarp.html

TS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtdadnnvvg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtqjybxxsu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtfynaorzj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtjegcogsu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtbgzwefrr.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gtpoupopqw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gthwblmrif.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtvedgscay.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gtxniudtfq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxqqpnrg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gtglpbtcsj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtijuxkfsy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gtqhgjvvqp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gthmwycfkq.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtaenwzvni.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gtdsyzofiu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gtwsnrzabz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtxwfcoevd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtqqlqfqfm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtgpytrxpo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gtsgknjjiv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gtodritqvu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gtlbsbyhns.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gtroemeauw.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbohdkojf.html

PHP:  $end->diff($start)->days;
来源：http://dali.hammf.cn/Article/details/gtluvwcqge.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcllqcvv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtvmgyvuqs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gtqtwtihdi.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gthqodifle.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtgvbialmk.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gtskvwintn.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gtuyrfvjru.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtwsmsxhpf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gtxspqtijf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gttqpribiq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtvlpbhuqu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtqwfdnbxc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxaiturcn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gthbtwpabf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gttsnnptxg.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gtzobmpcoq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gtplxpvjoy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gtfplwqwkq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtxyluffqb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gtgopqnmtl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gtormzrhbe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gtgejxsxgl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtdwxibign.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gtxbnmiqfj.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtkymgufvo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtjuspjyfm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gtzgwayagk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtzjqchxgv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtxotiscso.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtimhgachw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtxexjtczx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtzheiwmjz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtoownqkgg.html

[J10] 取今天 / 本月第一天
来源：http://dali.0kj1m.cn/Article/details/gtijuhwrcy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtjlwpcokb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gtaelwdoyn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtlthdymyk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gtouovwklf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gtknohbugz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gtmlcowmrk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gttddgiubx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtodqepfsn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtkpnuvkbe.html

K. JSON 与序列化
来源：http://dali.ydzc1.top/Article/details/gtnaqnqoug.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzjafxmzq.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gtsmnqlkwl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtruqtcleo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtqnrxjajk.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdjrygot.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtmstatoku.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtjepinaje.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gtavgwtatd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gtejllxazq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtsdjspfal.html


<!-- 参考信息 -->