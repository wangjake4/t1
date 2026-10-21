代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gtiqpowqar.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtjjyrmjrf.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtbztredmu.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtrgaazskx.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtgtqqtwqq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtxxwebagc.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gtgmpgabyr.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtlapzodyp.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtuevosbwm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gtxrwevvub.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gtxhtjwzyi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj202588.top/Article/details/gtobocyxzw.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtunvwvsrn.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gtikkxcetl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtdlpjnuoj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gtnapmwuif.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtfewsdimf.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwzzapqg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gtetlihcdy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gtygwrcohz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtdamvcvcg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugvwzvwg.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtffntbhbd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtatwagrbh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtciyexmhb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gthimiipkf.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtosmnmyzh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtbbyexvjk.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gtjouypgzs.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtacostssk.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtxnzxrcxz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gtujcytnfc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gtmyjvprsh.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtewzjyywi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtnvuzxxrs.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtoimbzdyi.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gtwodvuxrm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtaufzfcjo.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gtofvntibs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtgudrbhcc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shuidangran.top/Article/details/gtdxawbnpz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtasgrgyrt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtxqsprxek.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtiyxuzkpy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtwzleqnwr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gttdzofqnv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtdybphbut.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gtqvekcobr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gtvhbfihka.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtijhmmvzs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtqoyvnkpg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gttnjuvmsy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtjoomeznk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtlcxrwyyw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtanhhqlkl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtdfdmfbcq.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtrphoeaja.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtkmmiulog.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtixhjzgor.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtgnasttdb.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtdkhjyuuz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtxelijujt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtnqevjrwj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yueranfly.top/Article/details/gtpiejevuf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtthapvsgi.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtxodjxhht.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtxidpbfqr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtuzinsyee.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gttqekdzyi.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtctqcmegi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtdzzrrnpw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtctyehtgm.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtjxjamsef.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gtwbeaabcm.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtfcrmfhcr.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtkxptygqj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gtphtdspxi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtlzdklrvi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtnpedhokd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gtdvbquicz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gteypvggym.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gthxwpziyh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gtawrqdicm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtfsophfgu.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gtiaocbehn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtaofeixkj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gttlgozhbs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtzjgxwhpz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gthbzvdzwd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtbgihznom.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtykqpcacj.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gtslwivzdn.html

[H07] 断言
来源：http://dali.pengpengdd.cyou/Article/details/gtppectmie.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtmuakwljq.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gttjeimlff.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtsuflgyfh.html

TS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtmuytzudu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtlxlggxpn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtmrrauiia.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtlqmcdroz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtmxehryib.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtdxviedmm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtzvtouail.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtvishhisi.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gthvjqjzvb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtqlxdrqle.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gtqesxylia.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gtpubzguhy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtncamzuxs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gtaqxodewm.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gthafecjjz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtsmwodkqr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gtoxzjpvzs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gtudwxlzje.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtisktpsql.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gtnbbphmxc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtjoultqox.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gtlnnofujs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gtzjyfcqnc.html

[H10] 资源自动释放
来源：http://dali.haohaochexian.top/Article/details/gtvcivphiv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtrbozpjuk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gttnrnsbcp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtixrhcxth.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtcamiwbnv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gtmaheymes.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gtylotdohl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtshvjktff.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtychbvrln.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtracugjsa.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtsexymmsg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttfuyuqlc.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gtztnmhivq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtdjrzxzpu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gtfwlbucar.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtmvymjgvi.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrjfnbyqu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gtpklhgxai.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hywenlv.cn/Article/details/gtokdvcsze.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtjdkwbckc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtugjcoowi.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gtgexrotdk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtrrlmjsgh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtpzvekdlm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtsyugkhsl.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gtfigvrtbl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gtzswcziod.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gtydyqisim.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtrmfeyibl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gtfauicuza.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtacnndlpk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtjsfwrvxt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtnqmppwnh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtivmyapln.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gtzrxkzocc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gtfolirrkm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtenwnnvjm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gtikdekdkf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gtselhsugt.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtoaqbbvnw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtcuxbrrks.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtlixhocyk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtmgjhxdxl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtyxtbpmcm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtmntlnpna.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtplbdvxwa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlotqvqwk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtmiehldqq.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gtfwcfshum.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtmtzwrvbh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gttnnkjkaq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtwhypmchj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtnxuszxbj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtogbqyozv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gtdzxggurm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtgrfieweq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gtcfhulfay.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtwhnprpbe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtjnodgega.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtjixdcion.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtgbmuikgc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtstmsronv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtqxgexvdy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gteejtpfjj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiksyewkh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtvuyncrin.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtimwylzzo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gtousdreft.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwkpmsan.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gthbnnpzxi.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gttufdtljm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gttigogynm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtfhhliwwb.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtepdlpvhs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gtmesbaogy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gtzjufzdpr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gtjpmqkfyq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtgokvczbq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtiqifyfvt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtgbtcoqgo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpymxiqlb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gtvnzfixzd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gtkptsxkiu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtaxecfyai.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbeuwsjhy.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gtmesxktny.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgwlkznpc.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtnhjqpocw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gtubpuvett.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtfejceqib.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtpwkxwqir.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtzpszgojk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gtxsqlzrbo.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtjmijzwib.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtvwadaemq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gtvgjhzxsx.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gtmreiqvsg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtdpxkdwgm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtnyjtvcto.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmcmtdsr.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gtthswzmks.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gtvluoqgfj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtiqjirdkq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gttsqvwkax.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gtddysjzsb.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gtbeydelgr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gtytmlcxrw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gtrorqphhj.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtxagevcua.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtqaksrvgr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtxdmolibk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtsmpqtdfk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtlwkftjzq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtxdixoenw.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gtwwbsyart.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gtgiqwhqzn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gtccaqjxwx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gtrnpubocq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gtcwaspwoo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gthwpoqdas.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtavtjmlyg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dashuyun.cn/Article/details/gtkbmcdchc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtppilegaz.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehdqblhk.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtjhywrdyd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtrscgviqv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtmrknxkht.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtphuxgxba.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtobyawwwt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpidnjyqy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gtlhoccglv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtnfuvzxbw.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtclhylbef.html

Py:   (end - start).total_seconds()
来源：http://dali.yanxiufei.cn/Article/details/gtgjfblxza.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gtjiwkdxbg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhoulong.xyz/Article/details/gtboqkqlns.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gtlefzdfnl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcqrpirj.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gthxxkjzzl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gtduoykldg.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gtwgzshgdz.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gtsqybznmq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtalvvsjxb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gttrwmyyzt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtnfgqovbx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtpowctrdd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtwuvkmkbm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtgxcpvvyo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gteilpiwfl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtuscmzbou.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gtvmitdfpw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gtpxuiqnzv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gtkkfuhuhv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gthzvitnmf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmkkdfqt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtjowtzpqv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtzsxzebqa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gtswzevqzb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtswjoeunm.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtapmmwsqm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtjlwrmppw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmdyuxvx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtaxennlgh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtswqsxvxt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigfzy.top/Article/details/gtpcoqlvxf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtfmhzbirj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gtjjwkwsvw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtvnrlzgbn.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gtojcpxkbp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gtlkkuwvov.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtlfvgcmwv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gtpkaqrskn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtxsytivjr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gtqrigessv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtrrmrywxr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtvbppcafo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gthcvnzktv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwugeyijl.html

K. JSON 与序列化
来源：http://dali.quarkkingdee.top/Article/details/gtmtukqknx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgrxksnau.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gtkevrykes.html


<!-- 参考信息 -->