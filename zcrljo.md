代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtdeuodvwz.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gtmxayueeo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gtgbwlhbfn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtairlcdsi.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gtxrmwgoif.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtcgcqnrrk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtkdoizlfr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtrlmaxuav.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gthlfrkqrw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtahejvnkm.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gtqcutuulr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtdtfqggxb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtfadlkrzr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtelinsxxf.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtrlwhbrbv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gtfoutijxv.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtsurpwkml.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtcpxxxhag.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtuskbcmpx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtqjwodehq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtiaerrxnc.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtjiioqwlg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtfcatpgsw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhwuophh.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtthnoteso.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbbdmsntb.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gtbddwvxkq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtosywtrfa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtefjenmdl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtytxcszxo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtuadjixqs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtysgykxri.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtvikjtgmj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gttsqznpeh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtzhojigto.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtyztdgqtc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtcsvilbaz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtevtlainj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtzekbeqyt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtocatovmk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtwsmwxutx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtanhxvxbj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtxlpwtutp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gthkchaxnd.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gteamjnylm.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gtvhjjwkhb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtakowhxjx.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtzwvhqjwz.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtarslshzf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtknlqtnnu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gtvisonfrj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtjdnxmtja.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtbehpbnvl.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gtgdocuztb.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtbcffybmx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtvldsslpj.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtppqtpulw.html

TS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtbkmnvrlr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gtdhbuyxxm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtgjpglmle.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gthnjevqwr.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtwerjllob.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtqecrkugw.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtnmariels.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gtyuyhwhwr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwynweinx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtkliqyxdr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gtbattrxwi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtlsxrhdfi.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gtfrhadqbo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtjjdbumra.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtonbkkkxc.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gtcdjvcmxf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtylmdwtwx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtkpwyuyyq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtjwbkyogh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gtyufeodru.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtufuxgfxa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtnxljvddd.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtgvekqnei.html

[H07] 断言
来源：http://dali.pengpengdd.cyou/Article/details/gtglyhzccu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gtzmazocdu.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtpllpjrbc.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtttfywhxb.html

TS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtgwhzwwrr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtagqamgoc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gthqpnkazz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gtwgqeddrx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtjkanfsvm.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gtxboncfos.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtiwzhegjz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtwtxfhftr.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gtntanahbz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtipuagbys.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtvdyqcfdd.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtwrmyfzro.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gtqeyoufyo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriqscsfc.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtypacliyk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gtyuvkdvwy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ydzc1.top/Article/details/gtflpotxhp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtogcczddb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gtsyzcggdv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtntwmrxvh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuetiantiany.cn/Article/details/gthgkyipmc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtnpgkypkx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gtqgnpcxkz.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gtazaeobbg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gtmhannrwi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gtbljnuerd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtczkmbxev.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtfwxuzurh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gtodkzmrzo.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gtgchbwvbr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gtdalldaqe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gthflmxcpu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmjyjgnrl.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gtpkrbinuy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdpzjcrgq.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtgxctadsi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntqixfzu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtsxcarlxx.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtggwsfijo.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtjgvowdzw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gtxydmmvme.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gtwjuyjfcu.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtyosngllz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtdlekkrkq.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtynvraepr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtywbgenao.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtpdkzxohj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gtqbanaagy.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gthbsvogse.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtchtiwbyp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtkvaowdxt.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gteeqxwvgw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtavotlzkd.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtlyanagqk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gtajyplybk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtymmyqcyq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cashguo.top/Article/details/gtlljdplhc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gthzmpwumz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtiifcmfda.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gtpabiziju.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtdljggxhz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtzmobyokk.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gtybehyqso.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gtzxmsmrhn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtvkvsphyo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtesixkuhq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtbflerird.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtgltxuutv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gtwmmpidmi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gtokrcfdkn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtgvxvqpau.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gthkpsejpa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gtrcrgevcz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gtrolmrbbe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtcwywsxjq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtixypxtkt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gtcjlguiev.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gtnlofyujx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtltulvnxi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtzbqgtpzi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtudvzzfzq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gteeupoedw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gthkafgadq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtjvwtepfy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtujvvfzqt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtdwfqaeom.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gtaebkiuxn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtovglgqze.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtvldfkgnj.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gtogrkytdi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtgrdpipvv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtdymbssqi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gtawqekdes.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gtrvhsfqyy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gtqdanwryf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gtevbpbibi.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gtmidzwgxu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gtydkkgolw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gtasbzihqi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gtolrgcnlu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtfmeqfubi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtzyxqixub.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtmiymgoxo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtpzaeryqa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtzaflfgmk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hammf.cn/Article/details/gthbblphvh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtqmjkwevr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpduqjysa.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gtpowmmsmv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjpesdgby.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtekqsveyy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gtegporxjs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtmcinutcy.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtaefsnwui.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gteewnlwfy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzvxjfvk.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gtglfarwal.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gtpchubudy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gtzaijkyid.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gteedpfzso.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtekokmcbb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtpasrnbxc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtzsvlrtrt.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gtpcvmrmvs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gtvocwbbvq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtmemiqpby.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtxqhtodkv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtvfibwpvq.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gtngojmecc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gtabotbqmw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtfdifcphm.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtzzemfjxb.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtbrjhxdev.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtzbjioxxl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtslfpwqcl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtpzewcpgn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gtbapcozyp.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtusdroqpp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gtdupkxoqb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gtbjxeclac.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gtkoobfpqm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gthfkfzdhw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gttyqamznx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gtpbpdbfpu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gtmjssdcoj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbinbvaiz.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gtrtezevil.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gttmbrlspu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtdoqlcvxi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtmmogpbzl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtsjfhcoge.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zycfv.cn/Article/details/gtnljlecjc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gtjrhclesa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjodlbsp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtrpzrdstm.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gtxbgcjjdc.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtmndspysr.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtkncvkdvi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gtffmixvtl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gtlytqipxt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazjhvxvm.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gtnhqfeudf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gtdyhyaaxc.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtzjaovrqp.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gtmxngxvoc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtfpbgkuqo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gtigbghnsv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtmjwjhxpm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtoopjavhb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gtzjyaoivt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gtlhysapsw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltdotvci.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtgpoxmkog.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gteczhmerq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtrqndqwlk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtykgrfypz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gttwqdnzqv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtrvxvzxtf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gtniwvnfuc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtkjrujzew.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gttxztdhpv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gtasinyxil.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gtyelijdyy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gtltcaplrm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtxvgnskgn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtxiwjbggl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtgzjvilvu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtegelpsqh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gtgbcnubgd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gtetgitxzk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtyuzigtsq.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gtzyjuunws.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gtnbulracz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gthqqbhbdw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtwgrrqpvv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtbnseejew.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gtmdclvyof.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gtioexrzby.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gtemmvbkow.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtszwsfiky.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtrmfmqcoy.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtzwehmuww.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvpumjejw.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtbizmvdcn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtjubhsxwj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtijoxpcxa.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtajdomgqi.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtiogyiego.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gtgnuikwrg.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtgvqwrpan.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtwgniyetv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gtoiqjpoxa.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gtdroqgevx.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gtwkevrmwu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtyccisezd.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtybfqxgse.html


<!-- 参考信息 -->