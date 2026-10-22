代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gt2xseylvdb.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gt2vijharnq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gt2olhbbgoq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gt2hckwvdry.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gt2ljdgmava.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2uarvvzte.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgxluuco.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gt2algfucjj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gt2cwqzbxvq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gt2pzzvefdo.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gt2agbnspxm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2opgxzpfb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gt2hjyqsfrz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2hnbvkvbs.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gt2jogfdlfp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gt2znwmiwkz.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gt2hbhkdyvx.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2adfvkhmr.html

TS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gt2vcaxbusw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gt2fpqvejym.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gt2jyaipqci.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gt2uehvnvle.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2pneofjgc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2czgburol.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2edyuvawu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqomlwmv.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gt2rfaueadz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2euhszmmx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gt2ibzezfxr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2ndxrtuoq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhazcqkc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyhagfhl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gt2xuauzbvk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gt2jqhprbmi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gt2jzybwote.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gt2habkspyi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gt2lknzvzwx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2qliudywd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2vsiltrhu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2pulxphpm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2nrsrutay.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gt2fkjnuewh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gt2oghkafft.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2vzcuprtr.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gt2vtkygwaj.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gt2ikeziole.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2zacgtkeg.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2ostuhxlp.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2dpgerday.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2yfrefdgf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gt2tpiwojuc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gt2quhdvqjh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2efvtndlu.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gt2ialjmpkk.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fltfeydu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2sivmtdvk.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gt2gntoldwb.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gt2dgrsqyyj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2duxihuus.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gt2enmaivtf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrnainhx.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gt2dvmboyzo.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gt2envrcqya.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gt2cgwzxclc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plgtxtbg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbphmxmy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gt2bgbfsfod.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gt2kwgwfrih.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gt2pdieojjf.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gt2vdvlxyha.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gt2ypaqgnrf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gt2ccietmzi.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gt2qayctepg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2wyklkdlv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2izyrqdgs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2tanjhcvp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gt2xiszhltt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gt2ogbnmari.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2certzwgn.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2tewrmtbw.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gt2ykjnrzvg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gt2fqqdhadu.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2unvpghnu.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2jkjozxrj.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2ynaxlpfi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gt2mavrkbgi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2imkkoeoc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gt2trkrovra.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyyycww.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2uftqgfqw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gt2evaakvtm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gt2pxrnydpy.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gt2gxrlhiow.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gt2fenjwuwv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gt2orvgkzyo.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gt2vfiwhqiw.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gt2tvsqlvoi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenzaomai.com/Article/details/gt2coedftgu.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gt2sjhfgqvw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gt2gghvsvjz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gt2euszbkwy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gt2wlnakgsf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gt2muubynfw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gt2mwkejofi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gt2muczfraa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gt2gcvbyscm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gt2aihwucum.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gt2fdzueasa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gt2emkwxamu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gt2lgtrocoa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2rrdqmlmt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2rwgekxjr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gt2qyamhfky.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prjmevuv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gt2psqgixyf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2mvzotufx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2kddhkrte.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2hyczailp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqkejjyz.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rwngiiff.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2abxbeitv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2cyyfpmwp.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2ciazwhcr.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkxcsdaa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gt2ydlcbffo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2hublwsgs.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2jcknofdp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gt2zmexexxd.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqslylol.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gt2svqhndnc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gt2thxljqpf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zedwdtgu.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gt2hygugfmg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gt2ffmvmkeq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gt2itksugqe.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2ystwajoo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2vttsgodl.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gt2pqeviqab.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gt2tgyenokx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuhcarze.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umtjgsso.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gt2aybdbhpj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gt2quzzgezq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.andypj.xyz/Article/details/gt2fqxtjrqn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gt2hbltwhjd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gt2ovsfjoqd.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gt2ppnqbmet.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2zhuluxbj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2kzyyaevf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gt2mdlbbzug.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2dalmmuzs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gt2xhbolqxg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2ectmilkc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gt2vwweqmvf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gt2umknevkc.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2jxslosct.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.andypj.xyz/Article/details/gt2cjicpmsc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2lnjnfnle.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2yftyduvp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2uhhjbodf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llkifzel.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqjfegfa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gt2raspqacz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gt2mfczgrkr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gt2xexahxwh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2ehtcfrxg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gt2kpjndfzr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gt2qsilghqi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2uziburbn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2ptdjpiri.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gt2grzcauew.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gt2sibfbfro.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxvvtgra.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbfvpheb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gt2jdrxirno.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gt2gxswjoud.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gt2hyvucdul.html

TS:   /error/gim
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufjaiswp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gt2rkxspskp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gt2rghsipnx.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gt2kzgvdysc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnzklmre.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2hwcdgbah.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmviqrpn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2kongabkj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2veofabal.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2khqalagk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2gpnbyzbs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gt2arsfvczu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rylnsgdh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2evldqrnx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfoeokqc.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gt2hkvesoej.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2wezlwnpn.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gt2rqvsmtjb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gt2qvqdzknp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2ovmdwcgr.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgfryzav.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gt2uyxvujlc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2owwlvjun.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gt2atxdzfaj.html

Ruby: Time.now
来源：http://dali.cqqwz.cn/Article/details/gt2xnlgbmek.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gzhubu.top/Article/details/gt2fnqlhjfv.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2jodyvwbc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2sueohhyd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkrtuugr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2rffspqtu.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gt2jkzsnefo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gt2azcikcso.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gt2mousuhxa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gt2uwciqpel.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gt2ydcpliay.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojflzyaj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gt2kmgyprlb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gt2mswlrudo.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2rfglrsga.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2bmootniz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2jbitbxpd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2thezfbru.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2vmoyacvj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnxbzcdo.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gt2ykqfglcq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytftamyd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gt2skfgzcts.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2uwukeorq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.9152youxi.cn/Article/details/gt2tcfhmiix.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gt2kepubxno.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2dqtbnnvf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2ybtabcre.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2prwhvrjo.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gt2fusianab.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gt2kvrntlvy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gt2akiwzbom.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gt2gmhhumso.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2tdlehhgm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gt2pqrokbbw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gt2ktrzckte.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gt2ujoayjiy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2hiseqxas.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gt2rojtlegf.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gt2hxzumkrv.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gt2buinctjm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atghbevc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gt2qnjjbwqh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gt2qupxdumt.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gt2anxfveck.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gt2klmgfalr.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gt2ibydzwob.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gt2bhrpzfql.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2urkszjyp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gt2ykgowmjh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gt2wpjizbrt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sajhrsvs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2lunjvxeb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gt2zstecmre.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2juowczhy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2goldxing.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gt2habitlcz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gt2xyiejegl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gt2forggscr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gt2djblzmhr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gt2rvksnopc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pghgvgiq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gt2oomiebra.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gt2dajummfl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpsbpgfn.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2mfrgixxb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gt2djwytwtq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gt2eugemplz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjcayxcr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2rodnfvgq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gt2pftgaugl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zdqjudy.top/Article/details/gt2yimglnxm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gt2codgxqhu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gt2cqubwsfh.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gt2svhpffhs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gt2bzmvxiud.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gt2xxkrsjov.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2htyqfytt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2sgyueshh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2nsjolrat.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zyahwuwq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gt2zkqwrnqq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gt2jhobidhg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2quahqaqm.html

K. JSON 与序列化
来源：http://dali.ivvv.top/Article/details/gt2btrjuhzd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftmgexzw.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gt2dyhxsoqe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2fbqujjmx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gt2pbttnbfe.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwvksomr.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gt2frigrloq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gt2ksbppwru.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2ffulhnkw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gt2xemvvmot.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2pxdbnnzj.html

[K02] JSON 字符串转对象
来源：http://dali.aizwys.cn/Article/details/gt2vqylqzlj.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gt2mpqmganh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxuanxn.top/Article/details/gt2aievohve.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2evapjtrq.html


<!-- 参考信息 -->