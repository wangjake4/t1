代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtivryfmby.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtlrvvfddo.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gtzqprriyu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtnixfjrye.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtykuqmznv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtylgxjbzr.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gtdptvevsc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gtjefyikqq.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtqkleawcr.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtuycttfja.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxafnnfoe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtqmazhssi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtbngrzkyh.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gtjmxkrudx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gtldgeoepj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthlixczky.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gtybfutdif.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gthqhxlkfk.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzvyqtjx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gtssafbkcz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gtosltoiit.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtwhivnwoe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtuoggbeav.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtgavtodyh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gttvarcfks.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtogpusmss.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gtjnvpsyqt.html

[H02] finally / ensure 收尾
来源：http://dali.gogol.net.cn/Article/details/gtqpckrzqb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtwijrtvhg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdkrosdby.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gttohhmiux.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtgowovfki.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtjcuhmyjj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gtfvkrdpwz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqvjbvja.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtlhxiognj.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtgoexpghq.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtaeamjjwk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gttmvdrgju.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtkcfldlql.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtvxpeaekg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtekipnrnn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtkvexxtcu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gtbdhovpmg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtcwrtvkof.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtuhgyxayy.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtvdwvigge.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtzvqxoddd.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtkdsgfajy.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtktaxsbok.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtivvabqvv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtkxbqlnlr.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtmbbgnpcy.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gtnonojaln.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gtkdboogtl.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gtumsmwaks.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gthvvoyeiu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtfearrygy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqxtbdfl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gtkbsnrkxx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtraabtxwn.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gtbceghrtx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gtzxxxoorg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gtoupsuyqn.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtlmhckofw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtvekomzoa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gteizryhkg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtvmekfknq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gtnddvviqw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gtegycjyqc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gthakyopnw.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtlwvrvqog.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gtbnhdwumg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtfyzsiqzg.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gtowemevcs.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtrfvumafx.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtjuzhhngz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtsshnfhtz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gtrbrrictp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gtsapamgsp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtbbxbompp.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gtioausqvi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gtfaybkzbo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gtjvmygqot.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gtbvkubixb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gtcxttpgxz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gtlfxsxxos.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gtrzlsctra.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtofcgxbkz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gtfgcudifx.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtzlxwmlyo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtuaksvjzr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shzxlz.cn/Article/details/gtjnwesccb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gtyzgwediq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzhmfecf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtewrstnrr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtmffhraot.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtjctkrjmf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gtrhggqvbo.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdniaxql.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gtfyxamsqm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gtgityihyr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtjvudspkh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtazwkqgww.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gtuphmvrkh.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gtabtxrsfa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gthkrretwr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtijmhsonj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmxfubrrr.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gthttcskzg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthwqjrfzv.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtylxrhuel.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtmoilojww.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gtcdjzkbwc.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtnoxrwydy.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtrfeduccc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gtchlygdgc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gtclnlcezc.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtqfrxwcjf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtxuoikeoo.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gtdjeuthom.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtmbdsatvr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtjjfnnvfl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetcfnnpc.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gtryjveajo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gtobxgeszo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtinleumvp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gthpqrtlff.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtimjawuxi.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtakgfxgea.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmrwxqkqm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gtofmoupdx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gtkuljhtgp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gtkdnufyns.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gtntkuokyw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtzprgkrky.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jiagoushi.top/Article/details/gtxncttjcf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gthvmffhnz.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrimhpku.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gtbopsfwns.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtzffiqxaw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtodxtvvow.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtteckniii.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtsqktpduh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtayrimlph.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gtpnsfhzyi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtqgctasiz.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gtipqskpex.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gtkkezyysh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtztkyjjci.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtgjscsphp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtcrmujwdo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtmtsazuxi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtucuehcyt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtaoemsdju.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gtaoufqkxi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gtqpgyuvbh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gthwnbpdkl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtouwwrkma.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtowzxyfpy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gttanjbfmv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtucunksar.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtnecdkvrj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gtotioavpo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtmbmuimor.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gtzaegosck.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnyunjzi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsboqnif.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtvwjuxfqv.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtgsqskysg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtggjiotnw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gtwdlgpunl.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gtwrbadwqc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gtwoyhznmh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gtfymonwfw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gticecuklm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtkefjtcmx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtyupgltwq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gttxvbdubg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtgxvcwslr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gtbscsunoi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gtusxtxqmt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtqgtyjrev.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtodmcwyph.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gtzqyeuvvz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtytusvmoj.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtzpcpphwl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtvtjdvlud.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtjgewelgm.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gthqhcnxau.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtyxggdemj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtedbcyibd.html

Go:   time.Now()
来源：http://dali.yongpay.top/Article/details/gtginnhqym.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexzssufc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gtkaxkrydw.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtcxjrdgbe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtktzpaylr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtimepiydf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gtbaiwwtsn.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatopawes.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtjtybfadg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtmfwvfcbr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtmwacgyuo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnfngzyh.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtmxtdxivd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtctaeuamp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtfyvdjvmy.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtfofgmvbe.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtsjzkmlvw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtygbwarfx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtbpisimyl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtsrniwvwp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gtgwqlvatp.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtwkvxmrpg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gthqcodyuu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tian-w.cn/Article/details/gtazysuaaz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gttovdqqgk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gtinvcdbuj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtsxwudgvp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtihjgdpox.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gtlyakzlds.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtrviowcqa.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gtwvaqbkuj.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtfacabbkq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtjvvxjdyg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtmldcxshg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtfvxdjhwl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjvezart.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtxmxicsvs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gtknbxxmni.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gtxapvvfiv.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gtihdbuqgl.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gtjrofzmmc.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gtkytfihgl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtlfzjxlxg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtxmedthqu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqtpcdnl.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gtzutupbcs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtrvkobmgk.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gtueoyezbg.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gthlmqskar.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtcqooecdm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gtmzxcbite.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtypwwqrbx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtsyvsoyjg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtdhxetdhf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gthbhftemo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtiiziypha.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtrumcalup.html

[J08] 提取年月日与星期
来源：http://dali.gzhubu.top/Article/details/gtmzrepbug.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gtgzipzfgj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtjvirojuf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gtgmezsmgc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtyehkmazd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gtbfmkuuwg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtbibkkopz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtkaiumgca.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aibaodan.cn/Article/details/gtdgfatzud.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgudaewu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gtoxpcvmib.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gtrchoxupu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtxelxrvxe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtlmquzkxw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtgcbovnhi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjhdhxtl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gtngelepzt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gttwxbsmka.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gtdybxttrx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gtxmzeospi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtnnrxxfyz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gtuueonqlz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtbkohtxsu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gtuivfcejt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gtudnyvnsm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gtkqjxxdcu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwwjbegn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnizxayej.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gtinixlafp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtoluixhkz.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gthazyhdeq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtiuyxdbnw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtltonwnfl.html

JS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtsmceduxp.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtcnlsrcvo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gtgcoktuze.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gthtycvcfr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtkbmdavew.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtietnfvcp.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtxlrsydrp.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gtlvgbovmt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gtntnrggtc.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjhbznmec.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtfclwjnar.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvkcvuqk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtsijhqybd.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtcfxavols.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtyzvrpnbi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqwpupib.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gttldlvvjk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtkldkongf.html


<!-- 参考信息 -->