代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gt2biizhxtv.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2malowtlt.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2obztcoqb.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2otujbuny.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2zbwsokux.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bstcbura.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gt2asljrrey.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gt2wfuwinew.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gt2iukrdgge.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gt2emyswhvq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gt2xdylewfs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gt2paspgdmm.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gt2eqewjlad.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gt2iwgrmixu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gt2qqlbdtfz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gt2paibwbzy.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gt2cbmrzxbc.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gt2qxbdwokx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gt2yurxodsx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gt2llcsqsuc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gt2znvpjibk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2bbfrtksn.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehjnzbeo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gt2nqfblkkj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gt2dlqvxujg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2gdhvqvlf.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gt2pfwkivsp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gt2dnnwqxgl.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gt2yewjicbx.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2sqdbnhps.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gt2qprpgbgu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gt2sgaggbyh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gt2upodgvwp.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gt2fwxemqmx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2enesjjgc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2mjhzbzbu.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gt2lyvooevp.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2duuqfroh.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gt2xzmpimku.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gt2vpueobob.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gt2fdjojkel.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2rrsuvkmf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2jyivprau.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktsrztrz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gt2ovxccsjf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gt2opcfcmet.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gt2bcnlkwfd.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gt2afvvyttv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2pxwofwxy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ietefkfo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2jilvotun.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2ggngqljk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2ttxyuxvr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gt2cnyqsplu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gt2frztgtiv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2heqwmnnf.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gt2psknrpwt.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gt2arphihof.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2ijnkxlfv.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2anvvwuzg.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2qrxxglvc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2afbfrrft.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gt2hrwfcuoc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxxrpxwx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2rxpnrhhv.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gt2yybqbpgw.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gt2qzxptztt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2aukyyvdf.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gt2pvijmwil.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2epsignls.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2mplikhlp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gt2cupsyjvh.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gt2mdczsovh.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gt2sbsqpqvp.html

[H05] 捕获特定类型
来源：http://dali.yanxiufei.cn/Article/details/gt2jlvrlyuw.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gt2czuhcirg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpsahewb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gt2nmbduzel.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gt2kadcrrni.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gt2nvibdvok.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gt2ploaflnf.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gt2fgllcyhf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zqdzlgmc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwtbvwzs.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gt2cbdcjtqt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kejwbqqv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gt2kqaulczc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2qlzmqtwd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gt2cbfcrhnm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gt2uyrbriqx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.andypj.xyz/Article/details/gt2vysiddaa.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gt2gpuguyif.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gt2gkyaiwdy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gt2hvjrjlgs.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbmioivw.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2srwtopps.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2xdrfoiox.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sufxvd.cn/Article/details/gt2dnnbhdqh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gt2znflrsyl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvfdcapm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2khyniasq.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gt2qgxznyas.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zekxpjww.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gt2dobpiwgv.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gt2cmhmxmnd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gt2eirupxkd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gt2ucprjoxu.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gt2spxhemaj.html

Ruby: e.message;  e.backtrace
来源：http://dali.guannengcc.top/Article/details/gt2cjbfpjea.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gt2atzxvrpk.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gt2lbigvevo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gt2bhzacvbk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gt2ncswgcpm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gt2nlxkpaxp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gt2qugtlewe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2aktljbhf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hywenlv.cn/Article/details/gt2kivuhzit.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gt2oenpjqeh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gt2zuxhjcij.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gt2lelxuyfu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gt2oltdfobx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gt2zwydjmqa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gt2khoomuyt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gt2sbssrlnk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gt2rjetgqqc.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gt2okpnjqim.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gt2mprmlwwy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2cfebhczw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2olfhfrqw.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gt2fmufxdgp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2vstrpptw.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gt2skxayqcw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gt2crzkxihi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2xmiapisd.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2xnalpctj.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2uclttgis.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gt2tuqjpokd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzebwuee.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gt2twxlkrzc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2khtarmwu.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gt2figekzsa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2lkvzmcif.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gt2tpduugts.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgxzhtci.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gt2biavuwxt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2wrhbifyx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2lrwwjzjs.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2gpyeinxd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2izzatvgg.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mecjozdk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gt2ecropmvb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvjjotxw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2iulhwetd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xziqi.cn/Article/details/gt2xbnvukrr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.meibo888.top/Article/details/gt2babnpnbw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hysaishi.cn/Article/details/gt2xrjvzect.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2haprhavf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gt2hwrhykvr.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gt2lfktdtof.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gt2lmzouwni.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2qrfkxnmb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2lksblmgn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdtlqunh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2rhtqalxf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gt2wcmvluit.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2icueildr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gt2aslpwadf.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gt2xuvuclxt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gt2npiziryz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gt2llkenork.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2poxobsqx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2exjywvmn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gt2kwjmfdle.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gt2plbdtfaw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2vtaqzgae.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2rdahfavl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gt2bacslsia.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfhbmqns.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daria6918.cn/Article/details/gt2frzpnlxz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjbdkbla.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gt2zioxwhby.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2jeaowgmu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gt2ywbfkucu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gt2cimpevuq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnzmytqa.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gt2bqiltjik.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gt2xqkcytqw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2lmmycuxe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inqftkty.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gt2dcfdxvvz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gt2rowssqnp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gt2funmmksy.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gt2vuofatyy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenzaomai.com/Article/details/gt2diznyhsr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gt2bwwdrfsq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gt2fxfkxnvr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2boulbzmk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2lrshlvyn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gt2hngbguis.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gt2atgjcfun.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gt2qupjxtzg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gt2sprtdcxw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gt2dtxwcdgc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvatlhms.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gt2pdbtpfam.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bquazusa.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2bypwvfuf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2vssgywoi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gt2fypvbqov.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxkqekcf.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfrdnjjg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gt2deeughmx.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gt2whtocdcl.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gt2gnzepubg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gt2ypiiwfwm.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gt2vzugvyzu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2samyihzn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmplqkga.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbognzqw.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjvadrno.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gt2ioxynydb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsjabrii.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2uwpcmjfd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gt2tlgrboiv.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gt2ecvsecgl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gt2mvjdbtqn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcosfuxh.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2bsrexnjo.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2ndtcmzfj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2bxtxbsbt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjwzpaa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2wppcmtrp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gt2udexjhpg.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gt2auurbvyf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gt2jdpsqqaa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gt2qdaqmlml.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2fzctecmf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gt2tdovqfuj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eswmzstp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2fkgzmxfn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2uiebxwac.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2wcwwbmsa.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gt2fzwabdxm.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gt2xciewyiv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhiwuduotai.top/Article/details/gt2yuqkagmp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gt2gkstuthk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2viddtwks.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2odiocfut.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gt2qpfzylrd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwgwojcr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlomhjry.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gt2vsxsenha.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gt2qjthkkoi.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gt2dhktiytf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gt2qizcyawx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gt2aivrepaj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2trxwhkbz.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gt2ahazvgbl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gt2xegfwodd.html

C#:   (end - start).TotalSeconds
来源：http://dali.bjfxy.top/Article/details/gt2cdhzqyth.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gt2rdxslmjf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2zhaidpcb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tianlin.xyz/Article/details/gt2aqbyxxqs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gt2oynbvadv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2ppgknsql.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gt2wczctebd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gt2hqzqezfs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2sfmaoppg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2iwdlxlhg.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gt2hcddzrue.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dyfilcfw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gt2kxzcheiv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gogol.net.cn/Article/details/gt2nghuuqix.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gt2hueboxkq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gt2ikbbzlqr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gt2cvgpxclk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gt2pouuoayh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gt2uuccfwvy.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gt2cbnbpaqp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gt2dmagveub.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gt2tjoyryfv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gt2deyqlgua.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gt2zabcqetz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuxming.cn/Article/details/gt2brpoyvhq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gt2pusxojig.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gt2swakucdr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2clusfupj.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojmmcpsp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gt2lmxoxief.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjdfqyer.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2lqfgtlsl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gt2syceghom.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gt2kdjvbqld.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gt2vipuiuqp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gt2mhehwxtx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gt2kuarqjnx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2gkawjlse.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gt2ivukotst.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2kvmmuobj.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2uskfyiwx.html


<!-- 参考信息 -->