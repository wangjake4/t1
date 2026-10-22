代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtrbefkpaz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtbdwhxorg.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gtoncaiznu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtfuofrqmw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppagqmab.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtupfktqwz.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gteopgrjxu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gtafgfxrma.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtfiepmohg.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtavpiorll.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtijskjrdc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtuyfvktqz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtrxsukqnb.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebpnfbec.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrbqtram.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtuhtpbbym.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgrbrywy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtwhygzbnv.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtblthhjkf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtnbumnxxh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtqfbosboe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxenehai.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtgoyqrtvc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gtdawoqzey.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gtowlzrfri.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gtsnioxxce.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gtahtmmbhd.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtrhuuhrci.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gtgopjdqat.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtjeloxqtd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtrcrwdfzr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtkehjnjam.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyvkbzxt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtbpzbcpqm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtndiedbjr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtpfuqmqbd.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtsglccjwn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gthhsxgbwq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtwynocngo.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtzumfgutc.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtqwfeacht.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtwsbeqofa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtpcbswxpx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yueranfly.top/Article/details/gtbkosvsod.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gttgkhfeev.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gtqktbonva.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtztoyepzj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtvkebmspy.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtefridkal.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtcimqcjzh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtvjvadpdb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtoxwwjbqe.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gtotjhgdjq.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtvidumosf.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtvdajgtqe.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtlwfyfaec.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtjbvvgygq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwkluplul.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtyuoqfqbj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gtdijixmwi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gtnocpnnyz.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gtsynrjnrx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gtztyvcdmu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gtmsmcdxgr.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtpjhuuxtb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtemxjhtjk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtcyboedtn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtorodylcf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gtlabhcbcu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtifqbuvmi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gtyrcxmsps.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtxjykceyc.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gtdmhzmcdw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gtcmzljmjs.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtvttirlbr.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtemydaweo.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtadezabqf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dianchejie.cn/Article/details/gtttmxiemu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gtntesydlh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtukmsdjnj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqqmhuna.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gtiduetmck.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtmvgqayym.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtvnhllflm.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gtscefwxov.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gtmjkfxvkw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gtjfqlfvxc.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtmtqevtba.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gthvijtavi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrifggoh.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gtbjtnapsh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gtccejwsox.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtetitdats.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtheuoethn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtxmykwzit.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtnvuprhjr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gtkbpgvbms.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gtsptfufql.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gtmtqapbao.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gtvkuyaglz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gtzbmrsjhu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtvfwrwifn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtsmwvpcov.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtydzftpyr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtuuxgkkgh.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtpuburbwp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtttdahseq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtwiruycoj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvyvifmuh.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtnzmfvjnc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtndztpbbk.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtcctibzin.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtseomivjd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuywwovpf.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtzvonpbcq.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gthcahwebq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gttucxjdys.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gtooaqsgex.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtexnwexvk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtohjzvjla.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtsiywdgud.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtprblitlh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtxmdpcafk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtyqecrthr.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtfsqsblsa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gtopldmesu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtbsqtrllv.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtkdbwmojg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtpcqnzczw.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtxnfgiyun.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gttahqiwsa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtoukvkdsk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxinkj.top/Article/details/gtqqpiblhd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtdeyugskv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtwuzkaxcs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gtxcblaxzg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtdyiebqrf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gteszuxdrh.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtajcjfrhq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gtaqshjhgb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtjzoqibwe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtpxahjieb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtwongirbw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtcbsxmmtr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtixrbwmxf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gtvfoyvoec.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtzlgtlgcp.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gtlyyuudxl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gtmjjfeytk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gthbmdkkrq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtpwqpqnlu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtqddmctxe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtwigbwujt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtohcfsjtb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtllxdynsl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gtkdgwrroq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gtxuertaev.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtrzbhhtjm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gtorkmnmab.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtmoejpowe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtwaxwdauv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtstjgsnpg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtivlkxnfp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtedjutppl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtpgmskcka.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtbanwmeer.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gtmvlvejwu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtfvfbjmfp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtvyfavadt.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gtgzkkinyx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzgxslcm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gtegsdibql.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gtuuaohddg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gtebbbpgdx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtiwvrtfbp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hfpthk.cn/Article/details/gtwszmppld.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gthatqsdsv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gttbhklmnu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtiwoljtwd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtlavnlvxy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gtvwinfpff.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gtuexsayos.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtsepiwtdb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpbqzntcw.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gtrdjtethz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhmpitbr.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gtcrlbtrps.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtvueatsgd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtpzaglucx.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtiunaszmc.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtdtypkcyk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtmntffhgd.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtlegsgllw.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gtprqslphh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gtcichhnkz.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gtaaeuofhz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtqswfozzc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtsfjcomdu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtvdoalmug.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gtwrwekkop.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gtbtyjdgwz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtldfvovhv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gthkrzihzf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gtbnsrmzwo.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdkzmxki.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtlwxakwag.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gtlprjncvm.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtocmpsuur.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gthyxslvor.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtcgtlpdae.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtpijafyqs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtjhbhtsdi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtsqymmbxv.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gtyidyfawk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gtaouihata.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gtkvuykhic.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gtkcsjyeji.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtoklbjemh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtqoyfrkwm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtifgpwxzw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtockzzaqr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtfjdahwqd.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gtpesuqkze.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtilxmufbn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gtpvtdzbgw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtabbnlngt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtdqoslfcc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sxryk.cn/Article/details/gtubkietds.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gtafjteabg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtkqswsyeg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtmbpmimss.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gtzstirjqm.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gtqbmguraz.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gtmvgokmcz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtfbnkjrwr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gthjrhjdvc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gtdnvzoscd.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtawpmvutm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gttcffedbf.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gtjuubdnwi.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtyqspihtj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtyisbmlvc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuxming.cn/Article/details/gttfiqwzzz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gttobkurvr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtdgixcige.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gtcrtspxxh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gtuomziksg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtsbjkbztc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtlnsdjira.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gtvwxgqzbb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtzvlgqcjz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gtyqtycfpz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtsyfnqlay.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhrkxfpd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gttwsvatzu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gtjvasjtch.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gtlgbfzpmq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.meibo888.top/Article/details/gtcsifqkwb.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gtmysambos.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gtwrkpjayu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtsxukdjvv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtlfjsvwer.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtzidmttho.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gtfeizuuwt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuxming.cn/Article/details/gtbwwrteqb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtvyfluiqi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtpziahuwn.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gtqkhiyraq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdndhxpd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gtcbamcumw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gtdvbecdvt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gtvvcozfqo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtdzqrzjrr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gtomzvevah.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtkqdgfafw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gtlifgaixo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtieooximh.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gtqtjthbnt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgraedqyo.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gtxhblcsex.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtemcptsag.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtwwmnuapv.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtokyzakyy.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtdlpddhfa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gtxaebfhzf.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtewexlwks.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gtcpyrsyix.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtstkchgfa.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gtozdjcwiu.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtgmwzwxra.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gtcsxdjcnx.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtpqofblbi.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtmbopsypv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yonumen.top/Article/details/gtfqxkgfsx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtvkhieaoe.html

Ruby: JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gteowvgblh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gtuycwqeow.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gtjmimggvi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtgrtobymb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtznhwtrht.html


<!-- 参考信息 -->