代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlnnxxqi.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gtqmnervkr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtorjmjpqs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtvhdqnkmz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gtoskqewff.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtfplctcxa.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gtnzqfxwqb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtzhpajqsi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gtujkvmkmj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtsobbefgk.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtzznsxnii.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gtropvnqrw.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtnqrohkli.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtxowsibhz.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtovmsgums.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtpbdnrcyn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtxysloydz.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtyathofic.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtixlytanj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwaoewmxf.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtjausleon.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtalzybkyf.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gtbcaqelsr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtxlzdhokn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtpaztlaae.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtigllqnmn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtebrpanor.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gtizreddsr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtxgicioia.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gtjgxyzhhq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gtqpvuuxky.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtmwkrxkaf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gtlxdmovgr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtycgtdjpq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtmfuzcqii.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtzzerdddm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtngqlenqm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gtxsblgbsp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gtothrxuym.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtghjohrtz.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtlqlflugw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtgiszzflv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtrjxbjknz.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtvybcfrvu.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtynajoics.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gthhqzbbxi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gtzxhwnidi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gtzhmugcdu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtkkiaeuqr.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtnyzvrtbx.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtyprdgbkd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtpqxxiirt.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtwulfrarr.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gttiyhojhu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtdgfvppfe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gthazzxcup.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gtoqzygbyp.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtwzyluhfd.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gthidkbdwq.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gtwmyjsvhu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gtxppqrbgq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtrfuszfps.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtblhkpfqh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gticyaymfk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gtoxnijwul.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gthvfpbndy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtncadowjw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtydcwzrjh.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gtiiebovip.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtaylfkqxq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtdhqaxdth.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtxnbymykf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gtnrjhoviq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gthxmemxnx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtqorbffko.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtnfypwtwa.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtqwpitdgp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gtdrwimhzp.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gtsoxlnupb.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gteboiliup.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gthovecleq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dianchejie.cn/Article/details/gtpvkmcojk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtnriyqank.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtdynnuucf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtbzrsedxo.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtvjwklwni.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtegoxbxat.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gtdpstyoke.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gteelrpkqm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtygmwlcbf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gtxeyjrmot.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gtcqrdskqi.html

Ruby: e.message;  e.backtrace
来源：http://dali.316326.xyz/Article/details/gtqaghxowk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtgcbaxclm.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtcoxyrixw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zycfv.cn/Article/details/gtfkfnfwxi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtqwvskbqo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtinkwzrwa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gtzkexmmxk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtwxubwdru.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gteybqxuly.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtfklkemwe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtsfzqvvln.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlgjezvq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gtmihenwcn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gtdzqztjvn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtjwauotvw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtwkulxisy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtsduzeinm.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtafhxwkgh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gtewnedfvw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gtzptqruof.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttujcqdll.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjraemncy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvlqgtzbz.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtsugbznwv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtsrychuno.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtqzpccbkg.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gthsmwieex.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtyelkiioa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtpditavpe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gtxjtipoun.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gthjoqnpqd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtqnrcqhsk.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtkdzzgjex.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gthfrauesc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gtijkyhqed.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtyhthojhh.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gtwtlesxad.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gtarnuktzz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtdgwbjzqf.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtzaoswrjm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gthsbzuaew.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gtzhkbhzwu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhorrybh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gthroylhjv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gogol.net.cn/Article/details/gtqfzihqbj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gtnpigahdl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gtcxswdfcq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gtazezaonc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gtxjdujoqp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gtpyxumilb.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtmeknnzvd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtcxaruhbu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gthjfldfzk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtlkigyzzp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtccyzqfnw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtkjtvebsd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtcvntlspw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gtpisrjnoh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtwctcqxnh.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtmqlsydja.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gtjtdlywuz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gtsygrwcro.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtmuorqmtm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gthptrhifw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gtkaxirtbl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtxrkhqrck.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtluvhavew.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtyrqandla.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gtxraecfxr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtxrdigcue.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gogol.net.cn/Article/details/gtkpzecwcx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtfdfkkltb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtiummtmfr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtdertzyvm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yonumen.top/Article/details/gtsekcirlv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gtetheekox.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gteoyngcml.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtuhkkwuhf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gtjsvvpika.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtciyslwrr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gtfkwhvbpj.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtkvwqzwfo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtrwpppktl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gtpqcviwdi.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gtzhykgkta.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gtmbkstqqb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gtwzdzabgx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gtexhpdehm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtnyvdccan.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtuhkfbumu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtehzdthrq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtfjonrvvj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sufxvd.cn/Article/details/gtnyqzlxia.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gtezvrhneb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtkkmatjoz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtvuebzcot.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gtzshwxfag.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtwalptnwh.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gtyvpwgblt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtawyfsqhw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtloyzqlex.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtywjsndbn.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtzrzbggon.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtkzhawhmd.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gtidqzolty.html

Ruby: Time.now
来源：http://dali.jinqigfzy.top/Article/details/gtgeoeedzf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gtcihgqcpt.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gtrdewalzm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtgcjzqmda.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtmtinltia.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gtrzbepyvl.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtxvgjufgh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtuexqtypw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtfvesvvnv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtfrnnnagb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtnpicglzn.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gttzkoxltc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtoriztwyd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gtmrzscwpi.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtntpxdjyy.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtgonnpthr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtsghhsppn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gteswdaigd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtyrphpuxy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gtfmonkwaq.html

[J04] 时间戳与日期互转
来源：http://dali.yanxiufei.cn/Article/details/gtohxngrwz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtgufafbrx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gtxtdnqoja.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtccdovyvb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtotvrhvpd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtxluptkhc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtoqhduyhe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtmcvzuxwq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gttxqadicd.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtuklplahd.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gtqgjxjqfm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsjfmsoa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtegocgtak.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtrennochf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gtbrrmrmxc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gtfzarumem.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gtogylwliw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtzayuzmch.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gtlzuisnae.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gttplengnt.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gtmktwwdxe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtvljkxnfd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtujzlkceo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtxxddnzcy.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gtadfuojdl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtjzjbfhko.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gtwbipmeue.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtnpbzlazp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtkllpevrn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gtwiuoccld.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtleofwkgj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsloimdcu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gtwknqsmqo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gtbkdmvoso.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtxpdmtldm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gthhtceyka.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gtbjvytuph.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gtdaxuwdbo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gtiqanfxit.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtfpqssovp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gtbwhbvtwk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gtrwgbsbjz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gtwbwfcpfo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtixpcrfuy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gttwgkqkgu.html

[J09] 时区处理
来源：http://dali.hywenlv.cn/Article/details/gtbjvgiacz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gtezwxdsxp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gtprferhxp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtruvuxhta.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtwhthesfa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtuoniidls.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gtluczenkz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtonitbhzl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gtazpkmxmu.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gtnjhniuee.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtwcweacyt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtncsbolol.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gtdtnniqkd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gtptcbatbm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtznuexwkq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gtyjxbhmam.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtfmdjylkq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtqzhpqhhl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqrlsgklz.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gtlotmugqe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtvphdsags.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gtmbxbxrjr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtexhokaoc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gthbfwzfxj.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtojuthdit.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtgyjfxcuy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gtdunzvtra.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gtoxbeelpy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gtgxdrtdbi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gtotnegggm.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gtlspcteen.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gtupgjprie.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gtbupuhhra.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtjwhxjahn.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtqsbwyjxe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gtseldbyww.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtgofunuew.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgerpnxj.html


<!-- 参考信息 -->