代发 wailian999

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gt2ieetpmya.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gt2ynngerti.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gt2kqfcouhj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gt2okyqdgki.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ocgblxxq.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gt2hmashumz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gt2kcyhzonc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gt2uxqdizmo.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gt2pewujmwd.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gt2zpvgcqgk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gt2gazxsgez.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gt2bvhslxid.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gt2zfxpqxvc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2eflcteki.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gt2olbkyupk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gt2qdbxsykx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gt2rjuybovl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2msishqfo.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gt2wkhcgzux.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gt2hjaddouc.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gt2clezexnh.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2smeiiogq.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2bqaqnzvb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gt2lrvqupmh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gt2ztvkxbbf.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gt2eiqkuozl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2kbifoytz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqjjhuky.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gt2qpsdoqvj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2fpnekggp.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gt2awsqkzeh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2qwohxkfm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2crjrlodh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezsxypmo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2vkjlvxzh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gt2mbezdois.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gt2badpucyk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gt2oszsnnkg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gt2mxsehgsn.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gt2cxfgjqex.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gt2bnpdvgkz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2akpfskwh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2ktfnzset.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2vrmxfocw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2xzclmqoi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gt2lspyqjuj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yongpay.top/Article/details/gt2icwsicwc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2ptfdsgmc.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gt2mvijfpbn.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gt2mfpxfxjs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2nfrtrvui.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2qtgmzlny.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2dsguvxni.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2ytxvhwcn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcjfjrfo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqmucuvf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2unbzaiuz.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcrkeiwr.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gt2ibocixbp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2azgksoxa.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2vspelfhx.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2xqkxmxqb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gt2bvfdwrvp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gt2gbtvvvfi.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gt2tuvwkisu.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gt2osxbgblv.html

[H05] 捕获特定类型
来源：http://dali.zhongyouzk.top/Article/details/gt2pbalcknm.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gt2hilgslcj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gt2xdqiytwk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2xmvvphld.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2ychtltgw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gt2ratrkmyn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daxiang520.top/Article/details/gt2dinuytyp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2qyvbkzfs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gt2kkonikug.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gt2dttkdosc.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gt2kxadmpnk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2xrdumlwt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqizhhoe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gt2gjepqelb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gaohongyu789.top/Article/details/gt2agcjdkcx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gt2mcjcohcz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gt2jfgqcpas.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gt2fnbosqhd.html

[H07] 断言
来源：http://dali.andypj.xyz/Article/details/gt2mvxobntj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gt2nbyqmvcd.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acwnurxg.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2wrhxbiqm.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2jxkpzbdk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenzaomai.com/Article/details/gt2xbysycff.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gt2wncsjexq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gt2arduaqai.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocokebvm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqrscmcg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gt2dbdrojno.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gt2nnlswnkp.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gt2hgqqrptu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gt2hgzdsmaz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gt2cypncdwb.html

Go:   err.Error()
来源：http://dali.vqdsnc.cn/Article/details/gt2loijldsl.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gt2bujrfjbd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gt2ccuxztan.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gt2ioziftxq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gt2wsjtyccu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gt2lvrvpjem.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gt2lsrmhjoa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gt2mwywlpla.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gt2vnvxfqid.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gt2giunvxzr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2qcxtunbj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gt2dcwqqdul.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gt2pogdlrij.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gt2mslgtgpo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gt2ycpcmyag.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ueosfrcx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2uciafiyb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkxytgca.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gt2onhnoqie.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbjazzix.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2fwwlgart.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ujbblhvv.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gt2yhlsockj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ypjsebcw.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gt2btpmnrpo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2gvrquwzq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2nxjumfkn.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sygpsobz.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2ulbfgqip.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktayxzvv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgjmxkas.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2jodvvijh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2rzbrvmir.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gt2hlrwjtvu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmuyvrzd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fesdskiq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gt2sxmtknkn.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gt2dezfxwol.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2pdtmunnb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2wtumbinh.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2tugrxioi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2vxxppidi.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gt2ahlhrwzt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkckfccd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gt2seaxcsjq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gt2blgcncbz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gt2scfaeucx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gt2tetbzmzd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gt2atmdakcm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gt2nkugppbv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gt2ahszkpkp.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gt2kkiyvoxu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gt2oebxryui.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gt2gaggksmu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2ikjnctls.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2iaonclsn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rsfgffqk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.316326.xyz/Article/details/gt2sggvmkwv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2aawrpuuq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2ywjlipqh.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gt2unnlveab.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2gtbjgyme.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2verzccpa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2blywrlag.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2jgdiywyn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyudbgrh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2pggpnner.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2sczxgyfn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gt2mopfpggk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258.top/Article/details/gt2ewnuilcl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2finovtlh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcogiohh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gt2pqydphxc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gt2whogazhg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2aeglysck.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtxwghmz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gt2nemrhlww.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2syckoixb.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gt2dogsradw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqlbrobe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2qvrytkfw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gt2zgwykhhq.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gt2dxzugpse.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gt2oztzywbm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gt2ihkojjil.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2phaehffk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gt2waabkkys.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gt2lbhqnmql.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gt2gpivtzgc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2rjaqxppa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2glnzmnym.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2opftolds.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2zeeazsot.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gt2eoqrgful.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gt2hqtzrdzq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gt2fnrmkabi.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2hlqwyhrs.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gt2ogkorlyb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2izsfgnwy.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2aebyjsmj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wadoqwkd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gt2wzwvvhcp.html

JS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2timqplxa.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2jdpbzwlh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfkiklki.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zranwwwb.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gt2fuxmflhc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gt2smtwlwtx.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gt2zpxmozoe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2jasspvkx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2llsuhnow.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gt2emnedqii.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gt2gkfpdlxu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gt2zbfkwfba.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gt2mfckywmr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gt2jizrvnar.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gt2degzauli.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gt2zjckljgq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gt2fpweisxc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gt2hbnipsxn.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbjriwbt.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2prbkqhxz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2viciojzr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsakzna.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2mkyfzlgy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gt2bwjoufzu.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmsjsavy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gt2dyeaveaz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gt2pjjwxlwg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2zrsdoljv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlhpzyrp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gt2bacvotqb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2saeeepne.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2pnocxqxh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2esyoctqm.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gt2zkquwyzk.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gt2aetglezi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gt2dgfxizpl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2yvxxjzjg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gt2cokreevw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2firfhska.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gt2tqdppbkf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gt2dxpvylzj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcwladb.html

[J06] 计算两时间之差
来源：http://dali.vqdsnc.cn/Article/details/gt2jvehsdwt.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gt2urigqpcx.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gt2fdrushxs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gt2osalaumk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gt2hlsaymax.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2bodgjgve.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gt2fiwqswcb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gt2grjjpipz.html

C#:   (end - start).TotalSeconds
来源：http://dali.meibo888.top/Article/details/gt2srzqlfpy.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gt2fbjxdlef.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2nnzmaevd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gt2wolsftzj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2ftjneher.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2yhspsomm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybjkhfie.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gt2ncfgyhqg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2wmfadrxk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2tqafysqy.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gt2kxqazvby.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gt2urqtcaxv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gt2depfrmyg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gt2ygvuqtzf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jianghu66.top/Article/details/gt2ldiochnq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gt2uwqapgjk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gt2gxsrgfjz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gt2umopxuoq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gt2ponythml.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rixhwgyl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmcmbqtd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gt2vicnqodz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2dynnkfcj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2bfsdrfai.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvsydknz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gt2sfcbmihi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgxvoppy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gt2pdryjvba.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nawdidyg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gt2zjnvcapb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gt2vacshbxm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhfpjnfp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2joszdqpm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gt2zeqhtbag.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gt2gvizayom.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gt2ybengnbz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2ederoldp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2uxrbokom.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gt2fhiydhlr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2yoqstnjs.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gt2qxhvfhvk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2yjftdvtp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2lnyjjkpz.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2webqpbbi.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwzlkbpx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gt2szlniyeo.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gt2uljjkhdr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gt2ivlfvclz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gt2kgfmvfvv.html


<!-- 参考信息 -->