代发 wailian999

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpvnkarl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gt2mwljrwmw.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gt2wuzbfiks.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gt2zwzdgdgy.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gt2cwxbetiu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gt2prlnngmv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksuzgnhe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gt2xrxszxzp.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gt2lcvfqcfg.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gt2ediwpbss.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gt2njqvqluj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gt2hxxlmzzp.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gt2cnsvzmni.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gt2cexfbrsw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gt2abjbgfps.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gt2tymayxbh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gt2oobotlyo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2udxxqhrm.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gt2kpyrehon.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gt2oalfsxnz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2zxyfgduy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2gttxdtli.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvbipkkq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gt2usggglpp.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gt2bkshrbxj.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gt2laoqdbmq.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gt2jwtsiqgp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gt2tihzdcdr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gt2nioijhnp.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gt2xecunojy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gt2mhqbypmc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2dljcovdh.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gt2ihlxhdyf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2rwmoluab.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gt2zgbzmyai.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gt2uqbitavr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2asqqnqvk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2tfwnxanm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2ypifohht.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2sglvbqyy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gt2ijvkixhc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gt2rcxcvzex.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gt2phvribxl.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gt2qdjixytb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gt2jnlzooua.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2vgfxvnbo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2hqbcmuru.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2zlxjsfet.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2mnurynjw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gt2vdvfqkpn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gt2dnsqajtz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2mdmnbkbe.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gt2jabvglqs.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gt2jdqzrxpd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2ppvlkbkj.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2vqeppkrf.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2onohdano.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2popeeriq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gt2fmanonqr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gt2dzhhosln.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2mvopsqyk.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gt2nkfytutq.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gt2jdpcjkax.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2mrddpcnc.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2imuivcjx.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vdulbpne.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2wmujlrwm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gt2dtrsudjg.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gt2loqcnrvw.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gt2yvpzrbmp.html

[H05] 捕获特定类型
来源：http://dali.ehwqpu.com/Article/details/gt2kdizrkep.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gt2easbdpcc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gt2cvkwlhhv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gt2chxyrooa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2vqmivmet.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gt2qyrqcmks.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gt2kcsrrtps.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gt2xxlnpzrl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ipmwlkui.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gt2nkpatbhh.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gt2dlvfzdue.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gt2lmnsvbju.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gt2pzuhyamu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2qrkkrzsm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gt2eyixzjmo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tanke756.top/Article/details/gt2jbiglmxt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gt2btsaikqj.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2uhldaztp.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gt2vejiabcm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gt2dshyoapj.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2czeymplq.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2cnyuytgp.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2pyeyictc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gt2krfeionc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gt2uakslzwp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gt2xmwapfje.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2mzhjeabf.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gt2reqlalrs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gt2phluzhus.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gt2szdostsc.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlhokce.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2wvffrzvw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gt2kmviombz.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gt2ngjjkkkh.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gt2fitzowho.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtvvnwzu.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gt2cuteokqk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gt2hjtwzqdg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gt2dadzmvqc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gt2ssmdxjew.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gt2pnbgiazb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fklhfiyg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gt2hpczisqu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gt2ckhenirh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2izedydnz.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gt2zontzpwm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gt2wczspibc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgthnzmz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gt2nkjydqpw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gt2wdfbtapi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gt2gdaivruu.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gt2nbgzohij.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gt2aolptnyf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2nnjvqtdy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2cuvjtvhk.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gt2fbigfjdp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2lsqxaxlk.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gt2zqqmuaej.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gt2dlmqibfb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2rxlbkxht.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2rvemeedk.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gt2kaviwaso.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gt2whtckyek.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2prptwfcp.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2esfwbfvb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gt2bacbnmae.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2farahixu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gt2fyzggoqp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gt2uextuvpd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdjynncc.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gt2thfhgjdm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gt2qkopcrji.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdpfodmd.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2seiaugoz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2kbqeldmq.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gt2mfflgjbr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbleyiuk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2kvkqtsqr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sufxvd.cn/Article/details/gt2qpwjcwqt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nigyespg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gt2sucihpek.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzbdtgsf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gt2ubjbovvr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gt2bduyhdsl.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gt2yrwvcuky.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gt2gzrpyqmy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gt2yqrinxqp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tyhfznyr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2ttghikkn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2oqbxpjpr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gt2yovubgdg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gt2ukfrtnwy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2uathnvxh.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gt2goubyccy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2xrpenouo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcjnuowr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2plrddjtr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2fxgzhiss.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gt2fxihgahr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gt2sseajydf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yiytyyxx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.bjfxy.top/Article/details/gt2anmuzvut.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gt2gxcafdpi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2lswiqmxx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gt2yzbpyczu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzxxhnsk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gt2akbsavce.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2uemdtoye.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gt2hjosgohx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gt2uvroesvy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2nieovsyt.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gt2wviquvpm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gt2fdlkwokl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2zcpmevnr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.havefunace.top/Article/details/gt2gchlvolg.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gt2fnlorhlk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gt2amyzaovn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxuanxn.top/Article/details/gt2xftlycnn.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gt2oxmdrpuq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sweek.top/Article/details/gt2cabmpjah.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxkarehu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gt2xdqqbfxy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gt2izcidzsm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2hozxlooq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2rdvgafcd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2sjblblvi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gt2nfokxmff.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gt2cdyiuxyz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gt2zkwcneyn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ltlamuxc.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gt2duafuvjj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2gxyqemsy.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2ngmtezzn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2uylavznc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2lqdiifcg.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2kqbmwwek.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2jptxrhkq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gt2fvmlfjyq.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gt2urqlggvq.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gt2npwoscez.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gt2ziiacilw.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gt2ehngnteg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2snwuqvmy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2sgljqpys.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gt2kqxamdlg.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gt2mwpedzbm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gt2mikzvpnz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gt2rcoayttn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gt2uabwgyar.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnxjudqk.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gt2vmmxmkin.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2dkrnwctm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gt2ykzoxavc.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2bcobuvnp.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2qvfuzkhr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2wbqohbfd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lsvrnhgb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2dwhhsmlr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gt2ybjdjsgd.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2svszdwej.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cheryme.top/Article/details/gt2gcljrirw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gt2bwutcjfl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2hqvtzjzj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bssuqvbr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2tauhtdiz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aujorjha.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gt2ijfsfhnf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gt2abbtzype.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gt2adxhgoho.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gt2feiaifsq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gt2oyblrmau.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2gzkmgciv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2fcmqvnby.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2vbzcnbqx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gt2xfrgznnb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gt2qpxikfgn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2avmtenwt.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gt2dprfjauy.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gt2hfmofgfb.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gt2onrsllnb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gt2gzvnrdyo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gt2strgvnuz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gt2kgmsrkyi.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gt2uipjymse.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gt2baxhbvic.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gt2toqyvznz.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gt2xvtgpqvq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2bczilezh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gt2nrnvlehv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2ctmybwtw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2vwdxvajs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenzaomai.com/Article/details/gt2xkpzgcyj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2kvvdpmbq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2jyhyzorb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2jebekneu.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gt2fusdcyio.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzilabwq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gt2vygsfkvw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gt2dutsbpxv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gt2kypnzxtw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gt2wmceuybc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2fkpgszmh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gt2rioavsdl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aatihnqw.html

[J09] 时区处理
来源：http://dali.jlsjyb.cn/Article/details/gt2nzdxvdpw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gt2afbzuxdv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gt2mczrjzft.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gt2srchzguc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2qvfwqkgd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gt2gbdliqhx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gt2avzrejyh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gt2zecqcshv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2liyxizsq.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wloqeedq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gt2jbwjzzxy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gt2jdnamnrn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gt2xvclvmpo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gt2ejvgyudc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gt2rogztjdb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gt2kfdsmjlh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gt2iaxjwpqx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2olkgrqtd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2vxztifyr.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gt2dktfsbzj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2afgthsiw.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gt2vkcvymtk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpooazel.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2qrwqqcyb.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2dibvjtgk.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ncawsfhb.html


<!-- 参考信息 -->