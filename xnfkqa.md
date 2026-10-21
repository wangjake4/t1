代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gtsqcirmex.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtvykwqrmv.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtosvhutlg.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtqwlnkkhi.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtfwhiuxrz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gtftxknzhy.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtpjzothhc.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gtkwqhyqdl.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtcstywpxw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gttzogyxnx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtblfluzwc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gttqefqqac.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtgeidgnra.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gtqctiquel.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtkndansqx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdgcqeao.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gtwxwpdvee.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gtbvxrxpdx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gtoumlmomo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gtznzcxsxi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtgeeqkulq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtcitlyept.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gtsjprpkyo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gtfnezwkkl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtyzurumfg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gthgiadznq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtlynjerwr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtdhckgpbc.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtcifxgrgk.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtyeqynqqz.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtnlzgdlgk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gtanruetam.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpnjddqw.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gtsdgejqyv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtfuqcusiv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwqgyztcv.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gtgnyayozz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzrdajulu.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gtnoqcgbgb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gthpcyebxm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtevmavxdy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtwpozshbp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtmavumdtk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtmpkncphw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtjyggmecv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtlwcskgpf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gtuzhqndil.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gtoqmgqtpx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gteteijtxc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtlmnddjfw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtnrjntbmo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtvwwxookq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtivfzunjy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtdrdozpsc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtnbbppvov.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtylnwublz.html

[H03] 主动抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtoxjrezmc.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtgpndmemy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtehhygnuc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtnuhhgxji.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtdxzfzjep.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtqlpwdnst.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsredccmf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwormjcxi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtywxuefpo.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtcntzbynq.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtzxktyjeq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtuubaczla.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqgkihivw.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtifzzkmmq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttndjjxzb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gtkfuzmzca.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiaxwyhg.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtjlytlzcy.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gtoxzcrlsv.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gtazabgabp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gtflkmoadw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtfikyusrv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtjxfvtres.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gtbwytqmym.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzrjxpeo.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtlxgzoave.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtfymoyvgm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtyjikifcj.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtjyidpqig.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtujbrcwcn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtxwbaffsp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gttvifbtkh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gtdxmlsqdm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gtwlbahkre.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtmtsyvgqn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtdkqsapyx.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gtasmnsguz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtasdpmgmt.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtbysxmvmc.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtadbamapo.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtigefwtma.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gtaxwlkkpy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gtelchztjs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gtbomqifsd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtpqamibkl.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gtiudcliof.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gtpquseelz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtdtveoxts.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtlqgodftw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gtqqshixdf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtxfgtzadw.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtfhsnqbnf.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gttjjzillf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gtantdvshs.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gtfhbdybtt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gtqaaygomp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gtklzugxap.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gtnlaziohm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtlkqdqecf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtrjfdlckb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtcxtryewz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtpmgdokss.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gtfvjjsfvb.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gtlqaqxpbl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gttwzhsoep.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtwuwcdqev.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtwgawzfys.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtlwshnbwn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gtrdvfpmux.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gttdmgmwhl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gtmfkgutyg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gtgniyxiym.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtlygeszql.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtmxmawdrr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjiqioiex.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtabsugrwh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtjmdrcnem.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtwwwdqsvg.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtrkzgwbax.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtlpwjaesb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gthoohbbwe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtjkwelyuk.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtgasqlwmy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtqhnaugpc.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gtxijyvixy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtjhdacovl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtghobzuhj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtzwrxdrym.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtllrfhzjt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtpdieypvy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtooxkasbk.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtapkmbipr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gthnxxaegh.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gtuszkjowl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnoikeay.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocuravgt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gtwylbmado.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtpvjwaurg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgevwyusz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdpfastz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtaymclwhw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gtvrjfprkb.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gtvlcbipvm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtwtgrmrqc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtwbreictc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtoqbnhtuy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtnzvgrvdf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtenyuzule.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtpbrwogph.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.birdmap.top/Article/details/gtemjmkbgp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gturvfmyvi.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtlrjnskvx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtuojxagva.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtdnatnshu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtwobkwakz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnszhijw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gtwtirxovz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gteuxujzhm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gttcvixeft.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtchtxgtov.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gtlszmfixx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gthgfikcgc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtmpcwcuoa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtkuybfsde.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtdbxxdfdx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtazthzmuu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtellucrrm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtztemqoek.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtqjxhvvhi.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtagqejqvy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gtqygmoksr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtgsojozvd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gtzogaqvwb.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gtyqrdoewr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtmlpxopwz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtjaimjdoh.html

Ruby: s.scan(/error/i)
来源：http://dali.zdqjudy.top/Article/details/gtaoozcerz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gtxfkztpdj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gtrnayxlyx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hfpthk.cn/Article/details/gtonmndsdj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtcfylkmkr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtukldrwqu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtonexbtly.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtyrehpkrz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gthiwxlwbj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gtihncspup.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtengnpmix.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtinnnrzuk.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gtzmbiskmy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtitwncjau.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymblfofn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gttfxwbxjp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtvihqvxiu.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtbtdxrwls.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtygsojkty.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gtwtwkcbbq.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gtnixklkjn.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gtygruxfdj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gttkpzxhrd.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtdsxdfrqv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtnfujhira.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gttkguhubl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtjvowtsiz.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtkhybbxnb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtcbfeddjj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtsbyqplve.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtsaoskntk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtdtaqspgg.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscirhhdx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gtkcfukrvr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtdgncusfb.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtktarnarq.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtgbqvdjpd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtwvfrjbjr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtywegirxp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpcuxqbo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtllimzfow.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gtvhihyenu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gticksiabh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gthccxeony.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gtstpyehoi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nwbrower.top/Article/details/gtbeceixlc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtbsgjtoqy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gtxiumwhrt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gtssjjbawo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtjcfpcarr.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gteaznwerw.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gtfugbjoeu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gtgsfkkmnu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniomcell.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtuggtulau.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsebwqyt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gtrmbxatjw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gtnrypwmvc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpbliczv.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtlkrriykn.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtbmrgywrx.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtbkanqnon.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gtrwgldvzo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehdzljpw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gtcszfjzkd.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gtroyhcbau.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtswqumgcn.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtntezuzgv.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gteflvhils.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtdypygqxc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gtdslrhvgs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtduvungow.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtaxypcpex.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gtykdfdhqo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gttpzseypu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtlpvcpovd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtfjlcwapz.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtpasrzudq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtfezxsenw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmdgrobd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtiqhvdfvo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gtfgtkexof.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gthfmbfuyv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtdfxebomd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gtyzfaiiyy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtunrclpvj.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtntjoxggq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gtrmbdiiky.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gtllufdhpd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtgzuhjtou.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtpudhwpfs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtlxbltbtj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtmvngbczk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtolbpgtpp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtbetgfddv.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gtcduoefjo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtvayevezb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gteayytbxy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gtkwwymzxl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gtcznquiex.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtixerqwqc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gthaapnals.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gtwpvwbara.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtntauqoyx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtpwaqrzhp.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gtxalvssad.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtjcbrxvwi.html

[K01] 对象转 JSON 字符串
来源：http://dali.daria6918.cn/Article/details/gtvnyjzaas.html


<!-- 参考信息 -->