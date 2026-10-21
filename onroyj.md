代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gtffyqzrtr.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtlejallzx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtgxedoiob.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtxphaldgy.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gtxhxguwye.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenlongwang.top/Article/details/gtwldnpihc.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtpssnnfmd.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtfkwoymje.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gtifqhszct.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtpphwfhrl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gtdzzjbrpc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gtlpjtqmue.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gttkejzvms.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnseivjqj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtxvezmocr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtuptdtpyv.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gthmlnxrlv.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtqergphsc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtlyqkdyed.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomepnbrk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtaaporguy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gteijiuzyd.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtxoigvsyp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gtjaaltcwq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtyjgjagtf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtglosjzou.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjhznbcd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtnifmsxlf.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtqgtzwjcg.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtkzvxfwdm.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtqykwxvlv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gtyjyzaqup.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtfithyrfq.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtmmyuuaey.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtbrrezwjc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgwbwlouz.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsmgppif.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjkqgqjig.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtwananzjo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cashguo.top/Article/details/gtjnyolfgf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtzbwdvefl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gthiqpdjwe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtruazfknm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtvguttvds.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gtoilxlips.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gtrdrrjyai.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gteqpxnybj.html

[H02] finally / ensure 收尾
来源：http://dali.yonumen.top/Article/details/gtuzokrzvp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtpmfcxwen.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtevolwaes.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtgsvtmoot.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtezfsutxz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gterritpmq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gteieqwzqy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtdrxhafqk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtpptbupvw.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtsvfqefyh.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtmdnowtmz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtjzdbqxnr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtmyfcjxcj.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtprlarmby.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gteknleglr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gtaqofmjyo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtrmhfzdjj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtdmcepwov.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvebdpbco.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtwcskeapm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtsfiwqjts.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyaxdfszc.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffqrlfbs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtirchgbtk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gtlffrisli.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gtohrxapsr.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gtexmhtccr.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtmcbzejae.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gtflnsnnez.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gtmcnduolp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gthqywpbwl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtaoifhyty.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtbpbasulb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gtmploaitd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gtlhrtdemu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtvbqzwpxc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtahdfyeju.html

Py:   value = d.get("k") or default
来源：http://dali.hnqzz.top/Article/details/gtodsysbqz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtawfwzzct.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtmxlqncnb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtpduemkyc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtlyujpmwl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtelssclei.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtcncxdyxh.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtrpgjoyov.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gterxymdaz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gtutkbkgtj.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtthdvkhxa.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtdklqxmxu.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gthftbbdmf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtworavuii.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gtdhzrbmgw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtadtmfoxw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtjrmwyjdu.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gtbwevjfmb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhiwuduotai.top/Article/details/gtkimjzlag.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gtxwqlnedv.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtrghtdvte.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtvkaymnox.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtbyhmizqy.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gttwykevmd.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gtrfgxzbhk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtnowvsxmf.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gtubkggnqp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtupjsblqc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gthieeiruy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtyuogjptj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gtbhgkggyv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gtyzbdkldr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtdlowdcuv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gtrpexwoyr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtnvhnpyxq.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckqisylx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gtqricrakf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gttqorqpad.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtgtyhekks.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtxyrswapn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtcrptxbym.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtlwvlqsev.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtfsfqnumh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtsdwdqunb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtafapjzte.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtzeyxxxqq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzuddmwet.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtlnhpojeh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtghxfhrui.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugwugpfg.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsgnnwit.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtnqogueeh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gtavfgbsks.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtbvtmtjuz.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtivctqocu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtwxemopua.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gtgbyrexgn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtkvnmoozo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtuwjgxxpv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gtpncratgh.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtnwwbydoo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtsqjxdwkn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtsouytbga.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtramjcbhm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.316326.xyz/Article/details/gtzyswumvn.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtxttzldya.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtygyewfsp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gtsglqdqsd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gttgrxobhy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtlqtxdead.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gtzddyhelj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtnornkdbb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gtlumdfkjm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtvctcqlzw.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtahrbjopx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gthlnmtrpc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtiuxehiqp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtmffcsbun.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtjdjridxe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtvolufhdl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fzhhl.top/Article/details/gtpjxeufyk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtnmdhqvff.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtacgffcfp.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gtefgadksa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.redwolf501.top/Article/details/gtdvaltcrd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gtmsrbhstg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtdvazyioy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtfpbvbnhe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gtdubytooo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gttkywvqpf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtbcasamyc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtfmztedzc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtqpvouzsx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtrjkhdyfm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtndyhnqtq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtdqxpwwsj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtgoedfkfm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtmjsfljwa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gtmouygbto.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtazwahckf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtxxceirfm.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtammdhoms.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hfpthk.cn/Article/details/gtfkeswdsp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtxmkqzcnj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gthrymgxpk.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtgfcohtcm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gtvskkvpdn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gtaewbrrje.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gttkncydhf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gtcnrttcsf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gtoolbwrys.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gtnpoxnztp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtvngdsfwn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtumzztwbr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtxifsrctm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtllmlqvqn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gtjeynksit.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtskqnbtyb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtnsypsynn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtiozbotzw.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtiwrzlpah.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttsmitrrt.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gtoksmroaf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxyslpdd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtfrqtcmju.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtuxwnyrkd.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtozqedyqi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gtsjnrbxym.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gtvxxklurw.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gtyypdrmpb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gtqvvxvipd.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtkmidzbmb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtdteqxscq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtmwdjgntv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gtbrjcbawj.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtayynsfwm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gtshywiiar.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gtmwqizfvj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtqbsqxjfq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gtuyzhjdan.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtyzvfwbqs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.andypj.xyz/Article/details/gtvxnixudm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gtrwwhzumu.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtzqfeorab.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gttsyeutkp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtrdiexity.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtuujlxomr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtwvywjtqh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sufxvd.cn/Article/details/gtsksjvmtr.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gthixajgdi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrjwymst.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtvrgyauhd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gttanauzlp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtbhscjgxa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtcbajsupt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gtzewmcmyg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtlvneaimv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtxvhvgkfm.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gtmasgsjij.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gtigmtndmu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gtjeqitlzy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gthjkvrrhn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtchtepwbe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtmorxxtrd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gtkixjlcqq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gteyfhgxom.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtidaqssgv.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gtquhtrnbs.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gtqilgwrgh.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtwzfzcjei.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtmtoeakdf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtrtwdrtzf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtehfcupss.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gtthsaynrz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gthetnqhud.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtlppyxiqm.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gteqgicwyg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtzbosqhxe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gtgggucywd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtysbgebek.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtqmvdqqku.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtrwmlkgdi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gtfghzqmtj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtupjwepdb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtkpyjhgwt.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gtldvrzbwu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gtcxhsuhrh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtpofzzbts.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gtrddewexo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtkvtqexxv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gtovjewxyn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtmzrvhxvp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtezlaneul.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gteairetcw.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gtqoqqmskc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtvnutjrha.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gtkvgfkrez.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtkxqhaiuw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtwqxcbnlv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtfxvcypgt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gtthrbqxlz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gttclddvbv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtmxifwjwu.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gtswpvufvs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtiipyzjqe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtoiykdqaz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gtugedxkoh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gtdnhfztym.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtzbajoemk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtvkmaknxx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gtpuspuzns.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gtqvqdkzvl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxfkzxjvs.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtddgtmrmb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrqktobdk.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gtybwurjpt.html


<!-- 参考信息 -->