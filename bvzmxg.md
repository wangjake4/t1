代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gthayfftpq.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtxelrkibz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtelfpczcg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtdpfpvhxg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gttwbkdcsg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtihwvzqgo.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gtjygtowlm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtpldakxvv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtepflrmub.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtfuqsbzzy.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtfckipoek.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gtdrdizrvb.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtgmjnfiot.html

JS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtnaxvudrr.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gttglbiumb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gtrhmluppt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtuxlnhkan.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gtllgclaad.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtwwjzihsj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmangzxjn.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtggwbamxo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrtbadrtr.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtxitfygfh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gtchoqbhex.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtymzymfat.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gttvmqlldj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtzacwwtco.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gthveljsxs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gtorqwxynx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtzkfnelcv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gtcbdiwfkp.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gtefrzoflf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtgvduetmv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqgistfrj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtbheaejfk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtmsenutxj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtzyyunlkj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gtxxohyvsp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtztzobltf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtesptdhxn.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gtrrcuhhta.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtvyaqoubb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtexluaefp.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtbepxnzks.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtycllzmtv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtnhmkxvdj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gtqixxlfyn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtciliszid.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfqnkhlv.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gtjcispdom.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gtgzjzkarl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrmzqopx.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtacwhkcqo.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtfehhkrgf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtdxpqnyek.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtrauuvtgi.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtvexjisnt.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gtorqtfily.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtwqhqcxub.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gtmngswowk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gtkjgarmpq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtashzqplc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtcokxawnu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtihkbcaws.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtvidvqbye.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gttkurqgcj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yanxiufei.cn/Article/details/gtalhvluun.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuaupijye.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gtkcbftyhy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gthtnnoofa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtprmhywhi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtyubwhzfd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gtbkhgejqv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gtjlpivkis.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtmsotnzpm.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gtbntrnhdq.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtsooznyzm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gtkwjdraiy.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtdlvjbcuv.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtdpttctvq.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtjlspxmlj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtrfqbsrhw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ybcxt.top/Article/details/gtsqsubqpr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtcqafjqtd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtbumcjwxs.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjakjhsl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gtksngixaw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtkbndrlcg.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gtlyczhoyv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtmdigwqha.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gtpkkgxryw.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gtwspcnucs.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtugfvujig.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtygjikeud.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gtuudxujhw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtssxxdhgc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtcmnbguiy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtlinvftys.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gtjwwalbwb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gtcjstskjr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztlwpgyv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtrohtitsh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gtiazoqkwc.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvibwsobh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gtnilcteei.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangdashe.top/Article/details/gtkgazmvuk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtiifpeekx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtusrtmgoi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtewfovedf.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gtggseofdd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gtjrltoene.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxeydgxy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtayjxvqdy.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gtxrcbrfid.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqnipfplf.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gtalbjarjo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtieimbego.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtgrelkuew.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtltwprxda.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gttcvetole.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuxming.cn/Article/details/gtxszxoert.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gtdhhhdxgw.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtexxjvpxk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtydwtehle.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gtcyyaxxgj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gthvyezbjc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzvdtmrf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtvgglutep.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gtxwcjeawz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtlsmkremt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtbcjqyfss.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtprxxgwnu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtvguyvgsh.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtsyquwuua.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gtigjnnzwj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtgsalhsle.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gtsyhrjoxv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gtoqvupyhz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gthfgaejrc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtixxegnhn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gtoumcplwo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gtlykqixpj.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtfrycakym.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gtajfoqnuz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtmjxgpzox.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtkndugmxj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtfgukiteo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtvgzfcfjy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtbjvvezxn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtxexppwmd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtsyaqtdmh.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gthpkjgvwi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gtghkjxdbq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtjhnistxi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtlfvqenip.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtepqmcesg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuslodll.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtjcqgfenb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtaszuotlw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gtaevbvedz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gtzxbvvfty.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtysyhquuk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gthmjkxmet.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtwnczmdqv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtnsnrvare.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtogjytppf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gtljugiiyb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gtsordxlgo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtrfnvyodv.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gthbkftlpe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gtehcawnwf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gthhswobqh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gtoffrztgu.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtivszxvva.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtsgpoxzgf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gtqblmzprm.html

Ruby: s.scan(/error/i)
来源：http://dali.zdqjudy.top/Article/details/gtpegnhgja.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gtgvaurzru.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gtkkynwwvf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigufen.top/Article/details/gtkyyzebiq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtcbrncccu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtbfckurjs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtrmuceebf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtgtmyrynq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gtlzvlqqly.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrznaqoqw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtxovhxfjf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzdboxknl.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gtpfxqxatv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmqisvdye.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnnxnnrr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gteopfidwr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtyawsqbiw.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtcllcgjpg.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtcffqthtl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtycgzxjpg.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gtpcgvjxcj.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gtfpufrcaf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtdphebsmo.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gtsybxyoxs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtumzkboua.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtwpsdyxwj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gtcuyvwihn.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuluxgubq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gtrprqcoio.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgaapaby.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtfrcvlpgu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gtmaqvwgfl.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gtniqmdwaw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gtonhtsghp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhiwuduotai.top/Article/details/gtkpxalolh.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gteelurwag.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbjndybe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtgjhfgwli.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtifhcrtnr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtshrgstxk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gtblmrhwgs.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtahsizofl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gttarjpvyf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gtipfbyxnl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtldnggdav.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtiatbdzce.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtqckkcuvv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtqpsxvwsk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtrokppcqh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtyoqnlbbp.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gtnubamttl.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gtbhkeocyo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gtfblvwkea.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtxxtyopmk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtwljbpvvd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtixonhuen.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gtnazqahaz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gtuvuifure.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gzhubu.top/Article/details/gtommwqdoz.html

[J06] 计算两时间之差
来源：http://dali.nanxinkj.top/Article/details/gtmapwtuoc.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtpdyyorvz.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtdmqhxqkp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gtzycaybye.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtuzzotszi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtsmiarogn.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtcivnirnq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gtijtjsmcu.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlgpvztr.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gtlutoljvf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtiiwoqkst.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtdovszagt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtmxhqcdpr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtmspufxvd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtbukzahjz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtulblruhb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtjdknlyen.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtjwfnyjio.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gtxlccczgi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtszdeupnu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gtuylcnjhq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gtnmrkdlhj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtlfqbsmzp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gtbcnikzkt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gtswqlqcsb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gtojjbbags.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtrjzffmkl.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gtxmpqifqq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gtefcbyudh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gtuegcmofo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gttjlspwtu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtjrbdgkmv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtveidppft.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gtrvjiujxe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtwmfzjzrl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdbtisfk.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gtpgfbuxjl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gtcqdjhbvo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gtfqykpivu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtmumrdpsi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gttgsopwsz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gthizcxsjf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gthfkdsevo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gtbvreppkh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gtxcoarbxe.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbhxqfooe.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gtorfyjxnm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkczgdjoa.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtczhtpddq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtddxyyzch.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtpjtdfpnm.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghqeuksy.html

TS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtnqjesoen.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtfrtxeicy.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gtjjlwsydj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtvjhrydbo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yonumen.top/Article/details/gtenivogbg.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtyqvdtyiu.html

Py:   json.loads(s)
来源：http://dali.smart0.xyz/Article/details/gtegyeoahy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gtwagavrgc.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtliuchgiu.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtanbdsbev.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gtlvrtctio.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtwttrdwrs.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtjvejjuij.html


<!-- 参考信息 -->