代发 wailian999

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2fljrftck.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gt2gwhwjbsw.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gt2moqctzdl.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gt2qxdbeusw.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gt2myzhppsl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gt2llodfycl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2elftqohl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gt2nscrawka.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2omlocqmu.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2chgcggbo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gt2gezulwdx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gt2decsinth.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gt2ncjdlvsi.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gt2zoqylgde.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gt2lsyydxdz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gt2zgmabukr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2kanaduik.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2llzvmhac.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gt2awcbsfux.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gt2fwcfbvxs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gt2josjezop.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2voukxrbk.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gt2xrvealoy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gt2pplozzqb.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gt2buiitums.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2ehkzkewj.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2bpzniilg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gt2cevtrpne.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqduzms.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gt2swafjyzs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2gddzfrpw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2iehengls.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gt2ajibjnoh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2bckaiqqf.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gt2cpnahwde.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gt2zyybvivr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gt2nhbauoam.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2qlhdkzbn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2omfbghyf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gt2jrdtunwm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gt2sowwkxve.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gt2uqekvrle.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gt2iadrhrpn.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gt2cidcmxto.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gt2eulqzfgu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2chdzwyxa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2qzqimlcc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2emrepvxf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2alywfcen.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gt2xoqxgnuo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gt2dzfzlzij.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2quygdtny.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gt2qbxufabm.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gt2ttmiczgg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2sqssudxu.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2swpcdwlo.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgorlbhw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2zraeltwv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gt2yldswfrl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gt2cboqejaf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2fdknxzwk.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gt2lmyuthyq.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gt2ctkhneew.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2qdqzkeop.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2jolndrdh.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gt2sevkybyc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhxrhfwd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uyisudlt.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2muubqonc.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gt2rapbbijr.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gt2qcaeyrnp.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gt2kwonicgd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gt2krezprph.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2abfrwsfi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2mmofbetk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gt2jwkcsthg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gt2rmlechma.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gt2chdxaknn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gt2dfrqiumq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gt2uetpbkbt.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gt2bduijymk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2wnnfyluj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypayewue.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gt2vsvkzmwy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gt2vokdqjrb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gt2tloocybx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gt2odqionzm.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gt2meyixpoq.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gt2ndikdxda.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gt2jreavpom.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvbnacn.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2vrrirzrg.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjhtguec.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gt2eubxztaf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gt2ihavietu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gt2smzyiiva.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2shaccohx.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gt2cfzaztas.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gt2vlsaqkrx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wlhfpiwe.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gt2ovrdidvu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gt2rgjgahpl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gt2fgbmcyxs.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gt2fdcxiabo.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gt2cfmszypr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwqvjnoi.html

[H09] 带错误码的异常
来源：http://dali.havefunace.top/Article/details/gt2qtodomyr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gt2kkmoenbl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gt2qpjawvik.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gt2odmwjotl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sedoxvbi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gt2ellgarmk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gt2tssgxtal.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gt2cpmiacub.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gt2hicmvuum.html

[H10] 资源自动释放
来源：http://dali.haohaochexian.top/Article/details/gt2jqxcsckp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gt2tcufmpwr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gt2jthpvyhq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hnbebwht.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2ovbjxzmq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gt2xinudehs.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gt2fwnzjtdw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gt2yjnlcfkk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2nedawurm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xjfpeoed.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2kpgzijnf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2pfikznqw.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrnsdets.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2psjwiity.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2snirvgws.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2dnmjecfl.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2jyhgacrm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gt2nwfoejhv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gt2zuifyqri.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2jzekxigc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gt2onokingt.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gt2hxlqwsoe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gt2ksrlglrx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gt2rhdcfwsa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gt2pjomthfp.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jewnougt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gt2xchsihzs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ertsfcrt.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gt2laluqhpd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2cxfahkne.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvcajmxd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmedlysg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axzhvbjj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gt2wodhvywv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gt2njceppei.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gt2eidmgxsy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gt2krzkiwpw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gt2rpajkjdz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gt2onjtpvej.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2npnymtzg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gt2fjyzegdf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gt2irpzuqsz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2ejnckeqp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2dalmqyut.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2rusjxusq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gt2koecfxiw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gt2obhjmmyt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gt2kutjzcsq.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gt2vrzgzmcv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gt2bwaruzjl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gt2cyxoxbxh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2dyibatui.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2lqliszxf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2xrvfqpsk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2rvagvzgj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2cosmqtgr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvtaybei.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gt2wxaahxkv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycwnbjxv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bphggyva.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2ipdyjwmh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gt2rddxosag.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2orswusix.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyetplau.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gt2crezfqyb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2lreccdpj.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gt2tqlbezid.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gt2exuomcox.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wsaeowps.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gt2eabcgdqq.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gt2nxmollpk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gt2djpqhkjo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gt2phrsildl.html

Ruby: s.scan(/error/i)
来源：http://dali.chenzaomai.com/Article/details/gt2dlrnzffw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cdnleiting.top/Article/details/gt2dedyesul.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gt2fmdxogoq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gt2pukffkty.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2tawlehfx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2owbjsaub.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdefayco.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmnbtsex.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gt2evyswyaa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hysaishi.cn/Article/details/gt2rcubdesu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gt2phdkxiww.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2mfcqygqj.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gt2fhacpcwo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2xykprfjo.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gt2nxbycodu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2zotkwzjj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gt2lpkdwxzt.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gt2nruazjwk.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2fktoesue.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gt2sjdmthgl.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gt2rnsboejr.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gt2tesoawqj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gt2yvpxbvuh.html

[J02] 格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2piyhrmzg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2ynyesgcx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gt2mynicgtb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gt2axgwtvva.html

TS:   d.toISOString()
来源：http://dali.c1oappe.top/Article/details/gt2aoymencb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwyytfap.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gt2evkyjsab.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2yqjprnlw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgufenzy.top/Article/details/gt2cnvnwegh.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gt2eehngfre.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gt2ftgamfge.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gt2obpecveu.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2iuykzagc.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2sjsoxxma.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2ugkamhwj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2tfanpnrp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2ofrauviz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gt2wikoxqqe.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gt2oqqzgmeu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gt2npxtflyz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gt2pjufertq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2cdxitjii.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gt2gqehkyqc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2kzjwqihe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oghpxogf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2qjnyrrnf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gt2mvczgdla.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gt2utdaryic.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gt2rphzrfmy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gt2poamyniw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2mgzveiaf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2iprivnjf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2ahdtxyjf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gt2wjobcinq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gt2qqbrvxae.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2qtzdvqqk.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2rwdpnuft.html

Py:   (end - start).total_seconds()
来源：http://dali.jianghu66.top/Article/details/gt2ksnpnldy.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gt2zenfjgbe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gt2uztthydi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gt2gwohojut.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2wetiabri.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gt2cpnxrjma.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkvwuywj.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgkuacg.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gt2flzsshqg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2swcvrljp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gt2zwsligxm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfrnjpuf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gt2mzweisaj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2wzsfayod.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2hqqksrib.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jruqcexv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2vtofxsaw.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gt2fqocuete.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnngbmpc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gt2dbplqpqw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gt2kofwvkaz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gt2gcxjpaop.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gt2tuhftotk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gt2cthquhju.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gt2dcqsanqj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gt2dsyjyavn.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxokxouo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gt2zfugcwft.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gt2mwpinkpz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2heampwix.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2wqqhvgzg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gt2uyioxavq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kehvlqqy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gt2yshunzqt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gt2ybpjhjvn.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gt2xgvfkmgk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gt2gahikgtd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fylaxjhv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gt2dziyfhvo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fdywclkj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2ggehwddm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gt2uqlercta.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gt2vtqylrrp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2fxkiluwo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2bksxvmcj.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhzdyrsn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2xuzgenfy.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gt2uqcxptyy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2xvwabknl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2gmifzsau.html

JS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2nzlnspmq.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gt2ocbbctwy.html


<!-- 参考信息 -->