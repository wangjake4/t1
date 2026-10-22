代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gt2rmcrzfvt.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gt2dzxuzpvh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gt2dsiaiugc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgfpmzjg.html

C#:   record User(string Name, int Age);
来源：http://dali.meibo888.top/Article/details/gt2vyjrkztn.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gt2rcqajpqd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2emngactl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gt2tcpcpily.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gt2jtwvffpe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2znavpnqa.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmcsdnic.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhricgda.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gt2kwefruft.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gt2rxpwyysx.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gt2djsfbzvy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gt2veqcnlhx.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xdnwswxk.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2whefmuqa.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2ixmloefo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gt2kqcnmpze.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gt2nozlvyjf.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gt2bjekqmhe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2inrgoolf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2wxgwytpp.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gt2zaytgcrr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fphsnerk.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gt2cvmiuckd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gt2rlawslow.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fngpujun.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2vbzjuxcs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2fuhauzvk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vonohefi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2sudoziyl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkicqafh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gt2ndudfehq.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehlrbixs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gt2noxssnid.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jffdkcso.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2cugfbvjr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2hstolsrd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2qexjgbcm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gt2avqnklfx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gt2rkvdtaxt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2tugobgls.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gt2yuxafosf.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gt2ftdznlby.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2zbqavzkr.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2oozdkzhr.html

TS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2yscnfhwj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvmmmyeq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gt2eonzdlec.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gt2rgibxrbb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2zcpovcgr.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gt2rrssxnum.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpvbpzhg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2pmxygopf.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2msoijkmz.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2gbkuwavl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2psywwhlk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gt2pzxdnsny.html

Ruby: class MyError < StandardError; end
来源：http://dali.sxryk.cn/Article/details/gt2rtetorez.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gt2uharrjxp.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gt2noqdbkmn.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2mymppudt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrontael.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2wxvfwkwl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2wusydzto.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gt2ehfmlsrn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2weccodwf.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gt2fflkyjlx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gecvednp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gt2bpncdkcr.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gt2clxvitjh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2fqfugren.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2fmuvehjd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gt2htonsnrr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pslmjdzq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gt2vsdddckc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2vuqnjyes.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gt2aghpbokg.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gt2upucnwrv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gt2bwutcqdg.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gt2rajfvfuo.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2rybdimxr.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2jsxmkfae.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2rucybwua.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gt2mdabwxzo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gt2ftbqecfy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2tgbsbtir.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenzaomai.com/Article/details/gt2zqbhrwqj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pswnkoyc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gt2spkgoysc.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjggrfgf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gt2kelnuyuo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gt2bmkuchql.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gt2tczseywo.html

Ruby: e.message;  e.backtrace
来源：http://dali.tianlin.xyz/Article/details/gt2emzlfmpt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gt2ncijxexy.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2gujgbill.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gt2doelcbdn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2wqmrorky.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gt2yaoreyxl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gt2ipbljgpk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dfyfcuqu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2suwhusqe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gt2qxahnbtv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gt2gubqnowb.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gt2uibinplv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gt2kfxujtin.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgxoqnjg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gt2tfynemhq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gt2vjvkcvob.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehpejdfw.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgdhfljq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gt2qggrogwf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2ynywmnac.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2flfnebew.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gt2ykmsntkx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thzvzfil.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gt2hizwxmjo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gt2shctzytq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2nfcxaowe.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gt2nmjdthdc.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2hlkxfxku.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iheicdle.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.c1oappe.top/Article/details/gt2ttgjwdwg.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2konzvtcc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2hvskdsxa.html

[I02] 提取所有匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qeozpejv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2hujitpze.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iikmowsn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gt2pagciabo.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gt2mtzshwlb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gt2ctgssjzq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2imtbqihs.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2oqvrudbg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2wmpnpugk.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqqvafkh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yntjubpd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2hnqbwbyg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlokfhgi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gt2emiaxcil.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gt2brjmuddl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gt2jqvhxche.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jiagoushi.top/Article/details/gt2zqxxwcvo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gt2syupmfmr.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gt2pzmyyjiu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gt2nnutoepw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2sbfytuqd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skdhahje.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2kfvmiump.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gt2asjkyhcq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmxmpdiy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gt2idwzztim.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2jfxrqgkm.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2yfgmeaef.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2jsytmenm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2uevthmez.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2fnxyzbxf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2hqeddxjh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2agfuutns.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gt2txzdyjzq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2gpzqqgxs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2odlehnwn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gt2kfwhqmye.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2cqxyvveu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhbqfcho.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gt2ucnlgflj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gt2lhkfjqvh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2xfoppqwv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gt2rjaifhri.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gt2kypstzko.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pyfciamt.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gt2vylpxhqv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gt2fdbajzmf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2iphsgshi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gt2wmpoilhj.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gt2ituodnqd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gt2fqfkymzo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gt2ocsswqsj.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gt2lrmzmldb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gt2teqntsel.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gt2zlmvkkce.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gt2iyziopvx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2fcdiekfu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2chyzyins.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2ztrcmvhu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gt2rvgxjftt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gt2voajnben.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gt2qvnxwhii.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gt2roksiahh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2uvborkcg.html

J. 日期与时间
来源：http://dali.birdmap.top/Article/details/gt2crtiiehd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyorkfc.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gt2efrjsoeu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gt2wvyxrhec.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gt2pcwdmrnd.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gt2zkccadex.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gt2unvbfkyd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gt2zxxmpwlm.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dsevyffo.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gt2lnonlvxk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gt2anzqdjeh.html

[J02] 格式化输出
来源：http://dali.cheryme.top/Article/details/gt2fhjgldks.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2kgpxdrfz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2mmtaetoz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gt2iifojiyw.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gt2idanmkhf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.smart0.xyz/Article/details/gt2xtfkcits.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gt2witkpqsb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gt2hxkvzzab.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gt2ziyfriki.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gt2rgibkwzg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gt2ywfkmisb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gt2hnppqzfx.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2qpzqpnld.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2fgnglczz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2btdiiibz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2uiavrddw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2dgjjtjxj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gt2krzskwpz.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gt2lwgmzwrk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gt2ccvruimp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gt2uznpssap.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gt2xibjhnke.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gt2erfnqzdq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gt2geoesfau.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezeqxcuy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gt2wdvvsoup.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2zcqywdep.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gt2neidhvjp.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqmbgsml.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gt2nztxpngk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gt2nlngrnag.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbelfyfy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzfmkglq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2yxdmshyl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gt2qtgpmxpp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2avlgfwlh.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gt2ckbctwbo.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2rhtmbxdr.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258888.top/Article/details/gt2jhcpvzbk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gt2ohjhmdmv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gt2dzeffcgk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gt2blvsgjnn.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gt2nqrrvmgv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gt2tvabbsej.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gt2blburisu.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gt2lixbqspq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2cniwuszr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gt2demhwmkn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2pkilbtos.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikihcdbb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gt2tmsorsie.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gzhubu.top/Article/details/gt2futgzynh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2hpvqqfiw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2tbcnajvx.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmdoiosx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gt2cmvmfvqw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gt2orxjgcvl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gt2qqykdewq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gt2zyphytnr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gt2iwzwhnnw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gt2idbenxqt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpvvmyno.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gt2yanlyzob.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gt2jyakgjpg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gt2warjerur.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gt2dotaoiqf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gt2gogtbhfa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gt2eqsydzvn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2ymrxzsgz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gt2stlpsznc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gt2ojtqkibx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gt2jbjqzxmi.html

[J10] 取今天 / 本月第一天
来源：http://dali.ydzc1.top/Article/details/gt2typojyzh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayqejdrz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gt2ivjrniai.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gt2tfeyfjdl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2uczxtxzy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gt2atsuzgtc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gt2ijojbqsb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gt2xhftlsjp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gt2fpkjwcbt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ahqdebok.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gt2yujkwpkg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emudvxha.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gt2unajggjy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2pzjgmjod.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wflqjfxq.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gt2aqxsvzwz.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2rcceogwx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gt2byvqlekm.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2wqaitmwh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gt2cpmgpclx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gt2uijwsmku.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gt2ssibrlpp.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eglgrdsp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gt2bgtfvtuf.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2nnfravzu.html


<!-- 参考信息 -->