代发 wailian999

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtunkhoslf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gthhfrdgsb.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gtxxzmdmhy.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtilywpyef.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtrilicxay.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gttkdnzkrq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gtcnzdzron.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gtdopkvksf.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtgryefleg.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gtkrovudul.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gtazrgszoh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtfxpcpzpi.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gtlpgpdqbq.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtlwlgkgoh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtvdweqeph.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gtdxhyrbun.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtxgliidbb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtngcgqbpk.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gtckarzhdt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtcsluunck.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtccenflro.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtfovmcdyn.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqtombnd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtrqoplhtu.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gtkmknmlcc.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtwmlvmtlh.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gttllvmcek.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gtoaqzdbxm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gtfgcwjcyd.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtwhduvffs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtvubajvpx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtdzcpuheo.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtgtcbhnco.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttwldrevl.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtoszavylw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhiwuduotai.top/Article/details/gteqhjtleh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gtsuxbcwxv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gthesbdrnk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtfffuansz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gtmpfboswo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gtmpriogav.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gttvdhiyco.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtghsnwqhi.html

[H02] finally / ensure 收尾
来源：http://dali.jqgfzy.top/Article/details/gtbafpsezx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gtekhsjsst.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtgzzucicg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtozvwwjii.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtkpszalik.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdhteslee.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtapuxvbld.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtedcyauws.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtkdwoknfa.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gtlssxlqsf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtpbndcrah.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtkpivawug.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtpijikdhe.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtdyggmiah.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtopaqtced.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtahuqtqrf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gtnyejyoay.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtcksyyxkg.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtjpbbgpid.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtvqxiltsg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtotoebjtd.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnvzvtajo.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtpnunvpnq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtsmrbqrut.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gthyrzuqqy.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gthrwtgvns.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtuizlfrvt.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkwikqpg.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gtyqptbvyh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtphihqqfb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtajeoekzy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtuythrspb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gttqzwhhpb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtmntkcbav.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtpbvgntol.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gteyqfsjte.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gtuiehybib.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gtwwzkvxsk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtjxhrnoqv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtneffcvra.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtugwlaeqy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gtjfnmntjt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gtkobjgfbk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gtsoigjlfg.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gtezyrucuc.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtniuzxhsp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gtbkrfdbov.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtnknbuyce.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtewldpbix.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtncxkcbog.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gtitmpdkat.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gtghdqicvt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtdhfpxldv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtfuyprmkn.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtefdlcgrd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gtbpjbwzjk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtttkjpgjv.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gtmwbdzqde.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gtgbeqgwiy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtnhqhxjzr.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtxhiznsad.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gttdwopmoc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtperftuni.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gtiufjwkdm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtvtpvscfh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gtxildtmvm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtuiwhisea.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gtdfmxauvt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gtxtuwseux.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gtgmcndoto.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gtnbnwuitj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtpwjmzodt.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtheicwzkj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtbsbmkiys.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gthyyuhqqm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtcmlfskvg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtrjgtnapg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gtxcxbraju.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtwhhebcbi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gtmogtovry.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtbcrngscr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkdychvke.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtpojmvqqy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthruhzhgy.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gtmhbuwhug.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtexcsltrl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtwzajvptc.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtdcgdkrwg.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtvxnibylv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtkzunfwbj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gtlvadhhsb.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtmpscxkdc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtfmlszsao.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtceyrnybk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtuyasiliw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtvnruuohf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gtfzgtmgnh.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gtuudktgky.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gtuuwfxkth.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtmdttnjqt.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtnexrlnkt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gthbgmzyhg.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtrdromwki.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtzakoobdh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gthklomkxu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gtkczceank.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hysaishi.cn/Article/details/gtkxvyqezs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gtrzfdxytx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gtcojstiqr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtnapzvsel.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gtckeiooln.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gtgsfywjfm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gtrmximmsz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gtqeuxzboc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtdxbftrgo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtjzsiqxhh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtytimyiut.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gtswkwsyfw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gtcqrmmviz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzwxgqsu.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gtziefysvn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gtwhqtjwqo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gtphpacedm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gttdqytykg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtxirpvnyq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gtjazfcwdz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtxaozvkbj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtevyxvjrb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtmjpzlpre.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gtonmhwdpb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtjzqplivt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gtmxjwqxyy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gthntnxega.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtkuhzgref.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtbqltusvr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gtwaippuez.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gttjvxabck.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtdzawtndw.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtmuefioyc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtkaghalgu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gthryfzmsh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtyyuypgmw.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gtjlxkwqll.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtjoljfhyx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gtyggrzjbt.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gttmwqfsfx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtgofearwv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvocmizij.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gogol.net.cn/Article/details/gtzkoqpfgg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtnmbqnfff.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtwlgcuvcj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtjssxikwm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtacphaztn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gtlwawozpj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtkljjjzwx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtozfnghwj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqnwydkwr.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtcomxchzr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsvgfzglg.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gtvyxrlxzf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmccutfxo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtmpwsyrfz.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtcessegxh.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtbbntjfkq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtfenhdbro.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtidizdusc.html

Ruby: Time.now
来源：http://dali.zhiwuduotai.top/Article/details/gtooxjavru.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtwvqrmuva.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtoflbexvm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtsbvhksat.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtzxdwtcqf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtskbsxvbi.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtdrsticte.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gtkhqkujbb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangdashe.top/Article/details/gtarmzkmgb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtbjculgnf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyjxtlfo.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gtropjjcia.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gtspqtedgg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gtjxthjwpd.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtjrwaeynq.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtwbyvgmex.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtckioizsm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtuwgpzuvv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtpgbtwbyn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gtnkyujqbc.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtobrzapst.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtrngwhzkl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtrjbbsgxw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gtmzessegk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sxryk.cn/Article/details/gtzrktukvg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtgqccolph.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gtpcnknmzj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gtylfcifhu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gtmfapntlf.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gtigfypapv.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gtgcyvcmsp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gtvbbeysrr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtggcaywbc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtcykqocxr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccggdjre.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyikgwch.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gtkpokbrpn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhphviom.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gtmpuwwoku.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtcdkmcxsc.html

PHP:  $end->diff($start)->days;
来源：http://dali.jianghu66.top/Article/details/gtlxhzakqr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtqikmbsny.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gtygsxsegg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdenmkqs.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtbqhbewww.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gtuuohbrcf.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gtxywcpljd.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gtagmdlcjz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtpmqhppix.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gtsopowmnx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtnuogqksa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gtmvjcqfkh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtzhfmzbwt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtqpdgbbaz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnuhttid.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtcychdopj.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtommyhgdr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gtmsmyfjsn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gtfzthbtgr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gtmsgrindx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gtpyquduxz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gtsvlqgdtp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gtxodshfqk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gtgapfduhu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtnrdzdexz.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gtnqyoeylb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cqqwz.cn/Article/details/gtutcucyem.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtsachtwnl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtztttvjko.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruyzhtrz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yueranfly.top/Article/details/gtmvyipyuz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtnqwmnbtx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gtukuzftzy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gtzcbxeewr.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gtsnynsbet.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gtvrcnuhae.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gtnuauqbmm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtboxqnzdb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtxjfdvkns.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gtrfacvzht.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtrmuhftvy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtbdnxysum.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtsclarsft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyriqpajw.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtdavuuknw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkadwsda.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtlxqsjztt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtqgnbrdmk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtzttzsigt.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtieiqkyyk.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtovcxvfvp.html


<!-- 参考信息 -->