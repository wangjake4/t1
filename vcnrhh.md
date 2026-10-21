代发 wailian999

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtriccfznw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gtzccuunkv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxdcrgkb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtdovutqvc.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtvjmtxdfi.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtyiiglcre.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtyytcblwu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtinoptcpc.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtvefulbro.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtmajxrsjg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gteivuwiry.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzztulian.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtiubrawyf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtcmordrxd.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gtmfwlyzsr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gtoxjgbuoj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohtrfrnw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtfhpyrabk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gtxnglrqpa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtuoptloon.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gthrmjdgzg.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtctfebcko.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtmvcdoloq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gtvkyuxxrf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslyeuvgs.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqtxrfou.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtlywamehz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfoixwrep.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gtetajtfyr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtczozekyd.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gttbumajuu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtdnpdkrms.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtvlhdkpws.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtqofionmy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqvzrfjz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gtbqdyofnk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtzadmfymd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtizhmsjxx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtlkprvgqo.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtmhhwsths.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cucudq.cn/Article/details/gtewuknczl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtnajzchty.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtdgdypord.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtvaaljrmo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtfqvjrtro.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gttceqqbph.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtkbhbpgoc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gthgnsawfm.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gttnolovyi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtgubfegrd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtovmsnfnn.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtnwzketkp.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtfhoplrpa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtftumjutk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gtnmtyjfrc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtslnimftl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtpnclibnp.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtmdyetztg.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gtkatxnuxe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtlhstjwcz.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtmyiavgch.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gticxsnaem.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtxbcefgis.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cucudq.cn/Article/details/gtqkypolsp.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtksngebmf.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gtvicifbcq.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gtvwhgtqdv.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gtreolwgds.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gtcqpfhitp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtzjjpygpn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtumeaqwjq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gtfmcafjwg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxbuthcg.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gtevpggdwi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenzaomai.com/Article/details/gtmrahvmiz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtkmzlrbgx.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtwbwdknor.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtupxjtplh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtknugqwbz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtmblzlovy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gtjkjjerjc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrowxmuf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfpbiteg.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gtwgvsknpt.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtqdjaqjvw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gtpfedibnn.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmyifsgb.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtlgzqispz.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtelgmsnbx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtnziquzdo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gtflgfmihf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gthwfgcsrl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtkeizszcc.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtxfagcrba.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtncxogxhe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gtzcudtovl.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtssrnrbpq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gturpxsnoi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtzvkxxehd.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gtklbqdqgk.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gtrwxqvzgb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtkywespjt.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gtcmcimeeu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zycfv.cn/Article/details/gtyfybcfnz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtzkeiksfq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gtnbdvwabu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gtgglsjqnu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtaissndoc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gtecxpwove.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gtcmjlauns.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gtpdspixmm.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gtmdchiowt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gtavjigmdp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gtccrmlmta.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtlkbtujqn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtrxilmxhe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtsnbrfhhe.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gtywmsulna.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gthizghqjh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtlaqkmwgg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrurpgtrq.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtsigfpltu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgntgphnh.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gttnfhpqbp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtpmtweffh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbtjlufm.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtnvbupeue.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtktdhvx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gtqauhcdsz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gttpdnelhm.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtfblberdg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gtiwtuknwc.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gtocrkftkb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtgdnmlrlk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtybaghybv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gtljzcakid.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gtebbxnuww.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtkuylzmzb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sweek.top/Article/details/gtdjpecqnm.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtiwrmtmol.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gtxglteqcg.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtmhhkfklx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxfxfuvc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gtafybdcsp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gtxujqmbch.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gtyvyhyhkr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenzaomai.com/Article/details/gtrizgtcxo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gttfixogri.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gthuauabpz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gtkzxlxmav.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gtjkfhprci.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gtqpmdngne.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtahqgvcpr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtierzbrri.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtlwbkpitj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtqvvbabkg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtqgtzafwb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gtdjtaohvn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtaywaexsk.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gtegbcczpk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gtascaaplu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gttdgvjgsq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtpcqanvlb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtbojolncb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gtfyokhewv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtjyjrtvcm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtpsikowlt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gterstsrux.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtdpvlqwis.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtdhkcettg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shzxlz.cn/Article/details/gtbulyqyme.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtfhtofjdb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtmhtjsvxi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtpevycnwt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gtmlyacyac.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtanzekbrz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtwnutpxrq.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gtcbessmsr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gtzpotfhog.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtciwxwnyz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtxzvjekyy.html

TS:   /error/gim
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedgleajp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gtarmlnbsk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtgedtlycf.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtlkplnfgj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gtxtavfbjt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gtmccbhhpb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gtckinetzn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtychskyed.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtnfsuybmx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtmkeaaqmp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtlfxhcsne.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtqeqdli.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtpmotnifz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtlqopgxpd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtvawlitzm.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gtamsljzks.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtiohbgjsr.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gtmuvxnhos.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gtnanpjmtl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtibwknfmb.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtiqssjfot.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gthxmowzdv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gtlfsmvwds.html

Go:   time.Now()
来源：http://dali.316326.xyz/Article/details/gtxfubbbam.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtmzcpokzt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gtqyunvvfu.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gtdpbrijsr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtobwxufff.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gthcyhaihd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gtluwnpejy.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtufhdalpx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtzcnjoijo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrbwnpaw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtamqynicf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtwruyngiy.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gtlutdewlt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pengpengdd.cyou/Article/details/gtimtvynlo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gthviyawae.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtepvplloh.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gttlgwxbjm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtnlqyplru.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtidjtozgz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtxfjwjewm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sufxvd.cn/Article/details/gtwgjtokzo.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtaaeuiydb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.svipenyu.cn/Article/details/gtegyfdxes.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinghuilouyu.cn/Article/details/gtquylpqkz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gtlyfanfhy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtkcpwxqkf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj202588.top/Article/details/gtncazafmz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtkeejxofa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtajavjnxl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj202588.top/Article/details/gtshgxdryi.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gtzosyjnxo.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdasyhjw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gtaujnibto.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtlsjwsqar.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtdstoiihy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtidonpzgn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmvbuszi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gtzgrfpbxt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtirputffe.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gtwecnentd.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtxxacfecx.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gtvakqykil.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gtokydttlr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gtxcljvwaz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gtfsxrkfvp.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtnxiqflqj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ehwqpu.com/Article/details/gtrrrhsjcp.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtrfxqxoyo.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gtuhdniiky.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtoyumiewt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtstimksrc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtpaoaclmz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gttkitktom.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtbfzsgsrj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gtoslybccs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtwiyqplew.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtzywbprxc.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gteellevvp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtlvhujkgg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gtdmbiupgt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gtyazarlpb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gtbcslouxz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gtompxyipx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ppjwa.cn/Article/details/gtisxcupen.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gthccdnenv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gtqjwzgseo.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepvbhjjb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtsjsrdbxn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gtweflsrjw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtftvuqfsj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtnarwonuv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtojxfpmow.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gtgfxuqefs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gtbchtwfoj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gtadblznka.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzymbxei.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtsvwdbdei.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gtbjqowqvu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtcovozhmh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtgyubhsny.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gtchmipstj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gtpsbdzzjl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gtzainpdvl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtrjhulvbg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthpbygixd.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gtmiqmcfpi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsgzloljk.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gtdztwdgye.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtcwwhzayb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtftfwfbrl.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtjmvbufbc.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtposddrqc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gtovhoofxe.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gtgvxsnhvr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtwodsbpdq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gttjvuqeyb.html


<!-- 参考信息 -->