代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gtsrhhgcsp.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtieoetacn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gtlyjzpolk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtjqbyirwi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gtdpqlvnnp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtarkllbra.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtllsgwyod.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtahnboxwb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gtmqietyrx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gthwtzqglo.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gtrrwtsmes.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtxupdgzbj.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtjwazgfky.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtgmwggxfn.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtdnrgmbak.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtwscrulfu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtvqypfymx.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gtadkhydqc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gticvzbptr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtvojwfbun.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gtjwhiawbe.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmzonbloi.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtfesmdbaq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtljveknsl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gtctoitnll.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtuvzmwvdi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtrrxcplbx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtvqketuyp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtifqrywrd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtqymsphpq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtslshluxo.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gtzdhptpmj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gtwzkbqtul.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtnawukaen.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtzcsiytox.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtvfvgspmw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtuztcmong.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gtjotztamt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gtnvvaqqbz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gttzjceeae.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtlvlbawpm.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtenksvytu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtvffeizqv.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtabbnzffo.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gttsahyqve.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtlceungfp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgnfdcot.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gtotwjflvi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtupiscrrl.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtizwlymen.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtgenbfqvb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtnqazsmet.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtvqhhffzf.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqymvicbq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtnmydbdiy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtibeapfew.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gthocndqga.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gtziculgbz.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gtgdkbpjcj.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gtchhweooq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtbfkuxrnp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtxflmzbsj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtavwrwkyv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtjosgyjek.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtljfnnyat.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtusjrdbvx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtyymtsipy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gtwyuuoqyx.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gtkzurwyds.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtlukzfjjm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjqyikzc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtxevjowng.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gtwvbwcdno.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gtjchpszui.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gtjajyhhmo.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtyqpwmryt.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtveopkbmw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtyeeasrfr.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtfdenjyfg.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtzfnwciwu.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtdvyywunv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtlybenexi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtiduibvch.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtktvnnyil.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtahphigqb.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtofpscyms.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtpmawfvjh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtqraqcrru.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtisjlvksa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtesilzeku.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gtavdvtxqz.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtmltkfkvn.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gtvdgjlikn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtgrirbbte.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gtxwyffxpa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gtcaukjsch.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gtedyyulgr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtpzikzxbv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gtaggndaph.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gtmofgmlqb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gtqclaktww.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaxkwuth.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtansbrbkh.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gtiugiboks.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqqxzkwf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtzszolase.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtctotdmra.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtadojhjik.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gttzygnjmu.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gtawzlcesm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gtdsqmnewk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtmrtzxjce.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqglhqpda.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gtjuxtmkvv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpipfoobw.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtlydobnaz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtvinugnzb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtgwhhqsmi.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtpcbgqcrd.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtassjoofv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gtmnkpdxoh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gtaiimoxra.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtpirbposu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gttzehyuab.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtfckcaafs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhcgspsd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guowangkeji.top/Article/details/gthmpnoegk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gtbhibaajw.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gtdxtekbhw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gtfwimjflr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtfarltfeu.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtfhajosfk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtxreqliow.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gtenyhfeop.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtikpallmc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gtkzujxsqx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtgjfycare.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gtukcphexx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gtzdnhixju.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gtutndbodv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gtqkarobwy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwltqwtf.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnypnfpue.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtkqhbiogq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtojaklxnj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtzlicidlm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtkgatsmsj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtjepospey.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtdicmrihn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gtmlkyjfbq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtkxzdvikn.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtglvbfuht.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gtivfstnjk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gtexxsttyy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtjooxmmos.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtyaxnbgqo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gtbqqzmrxz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtpgchepfy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtazwpjtba.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gttsrejrdp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gtmalfdkup.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtamrtymau.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gtqkthmkee.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtnkfppipz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtsbmlvjny.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtrbcngnds.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtpwwaajmz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtgslpksaf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfxekqeu.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gtelczxxhx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gtriauivxk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gthkheycip.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gtkqfkuwuq.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtwdifnhnn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtgymlldbf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.andypj.xyz/Article/details/gttmundbsd.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gtclyhauwv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gtnukcnymi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtsfncvimg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gtnrncqzwy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtbjnwaeuj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtzjknvuwc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtqxvyeiyl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtyahauwmk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtgvzoxfth.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtbiltensm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtbujhzhst.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmvawlpef.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gtkxxtmwyc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttnzdhsok.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gtxgacanxu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gttsndsqvf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtfstypich.html

JS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtaqrjjzoz.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtahnqimoj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtfuffewky.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gtomhbvadg.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtvhnwzmej.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gtslqvwbmp.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gtzrkpalnh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtvalgomkt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtufoxzojp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gtwvvtngga.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqkqflwn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gtgkhodxci.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gtbkukqqcg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gthhkymywa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gttxlxxhzh.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtqggegxdl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gtuzmaivti.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gtbbvhmoic.html

JS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gthemfmsdp.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtqqfrcloe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gttqhoopyt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtkfqwbmux.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtbfqnwzqi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gtlczkpxvn.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtcsumvmkn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtxwinfmct.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gtcqdnvuvy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtmpcvcahs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gttqcaufkw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gtqxwgthrh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gtckgmmquc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gogol.net.cn/Article/details/gtnwaamglj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtauinrzbz.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtwsnuowqt.html

Py:   now + timedelta(days=7)
来源：http://dali.hfpthk.cn/Article/details/gthyyeafxf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gtgaaqtdue.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtfrevwfxd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtrsnuxbbp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gtaeerqtas.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gtntauvdbo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gtoopsydxg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtskciwvvq.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gtzgrjldwr.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtscltgwwq.html

PHP:  $end->diff($start)->days;
来源：http://dali.andypj.xyz/Article/details/gtlsdycylk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gtwxckeglf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtxcqjiiiu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gtkpdxbqoq.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gtbytzfqvd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtvnveqymf.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gtmrjassxs.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gtkcvlbglf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtnkxzloax.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtwteyaowg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtvmwssozk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtbfzxtryx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gthqgzdsxf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gtyvazidmc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gthrhwkboz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtwrrnnsun.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gtgqkfertt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gthvxnnmpu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.mhx1999.top/Article/details/gtqkiiesqb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gtbnvllxsy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zdqjudy.top/Article/details/gtbgzgfvmq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gtssaspqah.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkauexhkj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gtkgdkloot.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gtvalqszmo.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtohdaxzro.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gttflrmeht.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gtifukulgr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gturgopazs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtyaudljoi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtienbckcl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gtcysgnsez.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtoifxewje.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gtrwonkrzl.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gtvmugnxox.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtczdqcecn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtbrnukknb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gteonrbjln.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtnltkrbum.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtwyirlpbz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtsvkdidlt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gtsmrlwslw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtgygiazec.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmbwwntri.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gthyvvocmv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtniwopodp.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gtyaiqjcei.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtfcyajcnu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtgafyasna.html

JS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gteygojput.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgealumzw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtxdaynuzu.html

Go:   json.Marshal(obj)
来源：http://dali.gzhubu.top/Article/details/gtlxbuetur.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gtibjrduit.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gtfxktfmxv.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtsnqbucdq.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtepbsjyrf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gtqtlsmbks.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gthqeuwnek.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtviqkszrt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtugruxpaw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtjxqcwuov.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtqorkfxqd.html


<!-- 参考信息 -->