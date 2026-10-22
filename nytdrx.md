代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gt2cwzdqyne.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2lpqesviv.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2pvrxkdvz.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2aapkkyhh.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2mdqhvskj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gt2rbowftod.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gt2myikdskk.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gt2bqgpyjgy.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wejyjnxo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gt2zyjyoylt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gt2csmdolpu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gt2qykcpnjs.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gt2wonkhhsr.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2opnqakxk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gt2pqtwucle.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gt2nipkaybt.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gt2rimglbgl.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gt2ascmysmn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gt2mamoppme.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gt2alftzgtw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gt2xppgvvzk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2uufvpdwt.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gt2caslbghh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gt2ckakjnhd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gt2zkrfloti.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2bbqxoibm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gt2jqlowpxf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gt2cpqcbaos.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gt2fttucyks.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2xzswmtec.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nffanxja.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gt2ccfwkder.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbqlesg.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gt2ibgdfaht.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gt2clmcdbqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yosfidfl.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gt2rfqjefzj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2bayqomug.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gt2aawqjxdu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gt2ctituicb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gt2fghmbcwu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2vgettagq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2pwhfjohp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gt2lvjjkdta.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gt2mneobvmp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gt2xeitoejn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwtixnnr.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gt2oeydcecf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gt2bpbxtwll.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2hqstwrzb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2pszvfoxx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2bepxnuhh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbdvvlcc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebksnzgr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gt2hmlqlwvb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqkxmpyd.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gt2tkefzdpw.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gt2kthhhbgm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckgqfpxm.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2ekcgfzcx.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2vlmhpllf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2fsyemtrr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gt2ahmtfapd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gt2erwvbpvx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2wueliasv.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gt2zrednplc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvzrnmas.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2mbfaemlk.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2hrqiwcmi.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gt2hocufmif.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2bvwpnblj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gt2ixdqmlsi.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gt2sxliwndt.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gt2bzhnyjqt.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eepssflw.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gt2lofyolbo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gt2bkhksulf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2bgjhrrmb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2zpyvkjcc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gt2dggmccwu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gt2vwfjuilc.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuanzx.com/Article/details/gt2yhpabqeu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gt2gjpbylmq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gt2vhfsddyh.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gt2rdnoymmu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2hbbuujwn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2rlnqoyeb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2iljorxtw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gt2lczruzjq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtzjqvpk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gt2wuqvalml.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kydvtpap.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gt2ygeqgnlv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnrxnqco.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2gdhxztnq.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2msygpynx.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2gyyozqrp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gt2tyqymjse.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gt2qokjfncu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gt2rvcxfujz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2ejrgaoxg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gt2hlgjvsdx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gt2qoswtmgo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gt2famlueed.html

JS:   e.message;  e.stack
来源：http://dali.havefunace.top/Article/details/gt2msfgjekz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gt2vszpapud.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gt2okiborsn.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gt2gunewpnt.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gt2pulvyjkz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gt2yueaqpwd.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gt2wvpoexmj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmgpxnxy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gt2stypblzs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gt2zzrqxfkf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gt2nqpjmbtq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gt2efrsnbbx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gt2lloagbux.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gt2giurbubm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jianghu66.top/Article/details/gt2egmynbuo.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gt2beldxxxr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gt2hppumjim.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gt2wzbkrlvb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2mqgylzkg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gt2avbtxpks.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gt2tleqarhj.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gt2wrjllezy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gt2ydimwnvf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2cuzrzgah.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2qwjcypak.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gt2inatzyvo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2cntkptzv.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gt2msmvmcbw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfpkbark.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2lhgrmbwk.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2hvhvqfzl.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2sdhfxpdz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gt2yzoifdoh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gt2efolcuuj.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gt2dradqruc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gt2zkoxalqd.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gt2nwvgnuxl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzwmduja.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gt2svzxrlka.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gt2aqwcsxme.html

TS:   s.match(/\d+/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmnmwjut.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gt2lxsuvlxp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2zpnzgrxc.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gt2xkzvzgvp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2ncobmusr.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gt2cywbvvcc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2glvgikek.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2ssigebol.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gt2iouysdxn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gt2qoqfafvs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gt2ygwygplz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gt2myosgxvx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gt2rzamgjgw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2kqwnrwol.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gt2jevxzhqo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gt2xmbkaqki.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gt2cgbwgbzx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2lotvxsco.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iknjwigm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2toqydiov.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2ajrpwzxx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frsfxjht.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2utlmzcjy.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gt2fuyrsspk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gt2zhyejstu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2auitfieo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2txbdklab.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2itoffugx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gt2sxoyxmoe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gt2gohqitii.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2wanpluoa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gt2viqqxxgm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gt2hoxypnod.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2itqiemss.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gt2xhunoyqc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gt2fwwtoasu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2rsngtmme.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2pppvdils.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gt2zijeonmi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gt2ueldixht.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2ctkmxdgj.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gt2lfllknwe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gt2dahuhqxv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gt2thsphqpe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gt2xjdkcavm.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gt2husoqchn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gt2ggietxiv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yonumen.top/Article/details/gt2kglhpbvn.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gt2yhscfcbu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gt2xdmrwjil.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2mszxjazi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gt2ipxauzdm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2pwpuyoxa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bsnsbxly.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2hcvmqxfz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gt2vtoaivkz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gt2noppoyzm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gt2ishplniz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2wovujlic.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2voxbrgxt.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gt2uucikyuk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unvpgtdo.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gt2zmmgralf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gt2rcgtxftt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gt2zaqpdfze.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2chbcolel.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2wqxbobez.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bivuzzhn.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gt2ufpdygzt.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxgrkhqh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gt2akqoxnec.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gt2tzmhgmhy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2bjtwxyue.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2lrtcmkjb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gt2adrycopp.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gt2lytnbdkw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gt2gdvoargu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdstizk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gt2avsjmfot.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gt2xoojitaj.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gt2vlovlpjz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gt2zcghjsbs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gt2trethoqc.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lcyhnywr.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2thgnkpco.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2nkhrqrkb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2xhdxhduu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2zeyuiosq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gt2btvxfvpv.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gt2girshkfu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gt2fmimpioq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gt2qtxeztuf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2drcwjxqv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sxryk.cn/Article/details/gt2jlizdczh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aetoydfl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2azxqfiqo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gt2vjfwrxkl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gt2usvxpwcg.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gt2sqewesim.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gt2yxkiawaj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2deibssvg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2dxhuhhgv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gt2nyfhmhiu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2yxwaauix.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqvgptc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gt2basaktsk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2jvpuscod.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gt2xjaxuyfp.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gt2yfeqdzsz.html

PHP:  $end->diff($start)->days;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qybarlto.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gt2vlhusxke.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gt2givxrwko.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gt2zflraecr.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258.top/Article/details/gt2cayddmzp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2gmiutdhy.html

C#:   (end - start).TotalSeconds
来源：http://dali.zycfv.cn/Article/details/gt2zywwongi.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gt2yoazwnzx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2yqnecjit.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gt2ffgkoaet.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2wwneqvym.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gt2hlpfrhys.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2odryqkzn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2rdkqhhps.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2kzkurige.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2dxarcidc.html

[J08] 提取年月日与星期
来源：http://dali.gzhubu.top/Article/details/gt2alygwrxk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2pfphagpr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gt2tpcujrvu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gt2gjxnxqwp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gt2mojqzpkh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gt2cwfshzuk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gt2vnzxxwlu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gt2ytunssia.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gt2olzzccaj.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkyoyvhk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gt2hgtyczzy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gt2gwjgezyw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gt2vmblzhfb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2arecnavx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gt2wexcwasr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.havefunace.top/Article/details/gt2jygecysw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gt2nibhmvlr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gt2dfunumkh.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gt2mcovdhkv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gt2cqkoegdx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gt2ijbnnbzr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gt2gooaiczq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2rpnewvyk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gt2mfdlwuqc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gt2toteeoao.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gt2gelmvegl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2xyqhtoyq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xczrxhqd.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gt2fkikitkl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2gbzbiybr.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gt2aueujfzi.html


<!-- 参考信息 -->