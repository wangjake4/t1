代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gttgozqqan.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtqjaaqdvh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gtaigzmcgr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gtezblqoox.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gtnfkbwjdw.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtrodptizk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gtsddsfulc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtncbahnwj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtnbebauqb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtpqcdvnll.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtjgwwkbbe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtpbyqbjsd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtcsabltcq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtzzvkmhio.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtquuxvtba.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gtygesshpz.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gteltdtfrb.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtfkqoynnh.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtyigoinvh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gtukjasaoq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtzdhflaah.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtijdqyzah.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtrwdthjan.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtihcasetc.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtkspvhryf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjjvbkmgl.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gtdtrrrcxv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gtzcekxfrb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtojystwqw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtwvabgnou.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonzgbdae.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.kuanghao11.cn/Article/details/gtqrzqmezj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gtkhymanbs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jiagoushi.top/Article/details/gtqwfteyzo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtexlwpdti.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gtpwvpjngk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtbovnrile.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtnnfatcmk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gthpgimffx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gteyatrxpk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtktwoojiy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gtumxirgjy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gttbfoaecv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtmjowfbul.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtnjvzwzwn.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtrnxjusmm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtxjtcagyd.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtjfzvmvfr.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtbfsvadxw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtgtuorcjo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gttunptpii.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtqvyjpyph.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtjwbxambh.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gtvwjvntnn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gtegaervwv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtexbtwmfx.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtsfmcecse.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtggjzueyy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtwluamysh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtwviaqzbg.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtyuqchynt.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtkmsjdmad.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtigtovrdh.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtmrskyswg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtcyedrtzl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtiafnasag.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtilwizjiw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gtxinmsnga.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gteyhfqrzk.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdnkaphf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gtlebpsfwm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrgikdlh.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtqzuckwqg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtvgljhdbj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaasvfmqp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gthqrteebm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytnnhocw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtcpjrrfpm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtusserotq.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gtzklcgfuz.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtiezciicf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gtayjvyjrn.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gtcnyvrzee.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gttffruipu.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtyzaohhvy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtugszgalx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtydekyesb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtoaftvdfn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtplieawry.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtayocezrl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gtsucslsro.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtmmfasyzs.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtgsfpbian.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtxlynoqvj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gtykkqyspc.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gtgsumhztb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtgbqkemdt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gtzmownarv.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gtybyyaclr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gtzihtrhmd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gtvapayjzp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtsapiuhga.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gtvyduusmt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gtxpqmzujr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gtmpsopuur.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtfcbtucci.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gtqskzmmxh.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtyphsuusu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gtazdfqybx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gtqjcfodcm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtrkifpgyh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtncbagltl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtekbhbiif.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtbjscdirj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsxrkwtr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtmnsdtcht.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmjumdxni.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtoyakjsyp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnggohtnc.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gtrhpugrti.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtjbibbdhq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtntgorzte.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtpaxcrjti.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtokkppchu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gthkgixspo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaqnjhwk.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtaxdbpshj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtiedqodgh.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhzbnitl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtpflydpgy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gthkvhdmkr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtunfabaun.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gtplpkmbfn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtdpuodgvp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtnxmsglon.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtrujexfpv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtzinounmn.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gtnnrpicrc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtovilgzpt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtwjtyjxqt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtwgswaqkp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gtpfghheol.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gtfpvxzins.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtbdzrbbzd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gtojttbxww.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gtnixdjvgr.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gtpbbkmqmg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gtphsmdjfo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtcxyfstyn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtaldjseri.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtbozcrrsu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtfqtwbhoy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtumukmxkt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaypadpe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtkddmvtzu.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxycrvlbp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtuchwbril.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gthkgwcqqu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtsiievkog.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtrziqrrge.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtmvdrtjmf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtklnjauwr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtblzhicef.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtyqtgbkkq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtgdfukrjf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtbrdtdpmd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gtcyobynnm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtqrtosdig.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtcwnusoij.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtjiaaevdh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gtonmeodqs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gtbtnsrlyw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdufxzhoc.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gtkuvvlics.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtegrggdgd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtcmgyvhgt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gtghwzjayd.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtgdzfvcxo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtmcqfjnnn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtlepkaiqf.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gtabnlmaez.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtvibtvgtx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fzhhl.top/Article/details/gtzkwtwqgj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gtgalnzine.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyfbgauo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtaypnorlb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtsybkcayr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtjsdlomnv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gtpvkzhsuh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gtdqwrpjwt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtfddbxchf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtucvpzlby.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gticzkuiaf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtlmqmcdge.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gtroogvaun.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jlsjyb.cn/Article/details/gtnydgvlhb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtvnzcnmxc.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtjowkqydh.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtzcktaekd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gtxilvjszf.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gtaldfasox.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtfzhcpqak.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtwarlbxwe.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtzuqnvsiz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtyvykfaig.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtrcswaqeq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gtuwrgywcg.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gtqbotmlui.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gtiiknycru.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gtbmtbpqba.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtndqvngpf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gtdwfkdxuq.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gtfkoadvta.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gteofjpcgh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yangfankeji.com/Article/details/gtaqdirsul.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtufhxlljd.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtmkbchgxd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtxqeyvkok.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtaecwxmhd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtigqofvan.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtnpjlsvwx.html

[J04] 时间戳与日期互转
来源：http://dali.feifeiyinyue.top/Article/details/gtbjkfbjuw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtyeuzksfa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gtapmuhvbf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gtalgfaodp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtfqcsdwne.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpxdpkvi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtxyrpnhqz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gtulfcqhnt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gtrhfrmkcj.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gtknnpexia.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gtvpqhfiew.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gttvsfpbzw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtbhsifccu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtllykwvbq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gtztshyotd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtcgvkbmjd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqzcntnr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtesouykvh.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtpdirhncg.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtdqahvpea.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gtzevbbxtu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gtuhhkguce.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtvwqlmcjd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtyilclnyg.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtyuuhvtuj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gtqbkrwndd.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gtlhrnukwg.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gtpzizompn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtwymlbxne.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtnlfntwnk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtxgpzojll.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtmynxnwze.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtkjbkcrek.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtvmeakkqy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtrrkwsnty.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtpqrxycsl.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gtbinxrrjp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gtsxogzzkm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gtvedekwrw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gtummcbvyt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gtsflfzbvb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gtquucytqp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gtyulxarri.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gtgocndvdd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtylovulbv.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gtkftnoxdf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamnwuuiy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkogewff.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gttpoapoys.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtffbkfsti.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gthrvdesbp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtukfqvomu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gtnqvazclw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gtryetynqq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gtnjvaxkab.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gtiorcdffn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtdmcvodtj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gtfsyyhift.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtkosrrmqf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gtsvtrjvfd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gtqbcgkuln.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gtjedptrom.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gthfiyxvzr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgtlzjqqf.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtjvchjwyt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswpbsmtl.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gtpxucuggi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtgjarkdbu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtangictou.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtjvijjzkd.html

TS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtydbbvgbq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gtbrbaduwg.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gtbuvuetrl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gtcttqrjow.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtomyixfya.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gttcdkgjqp.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtitxpmurs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gtffgcvrcs.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtxdhdujqf.html


<!-- 参考信息 -->