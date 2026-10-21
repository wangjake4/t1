代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gtqhmnzgfz.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtxkjrslna.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtalapvwzy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gttitvqqak.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gtorwdmcjj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtufmscrsd.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtcrzvvqsh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gtrujndftk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtqumknfdj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtptheyrhh.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtwxfjkntf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gtfhuihymp.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gtfxcizyzv.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtfqqrnyxf.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtfbtgambe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcfrhfsy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gtanvlvjsn.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gtsetafcmr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtjqhyduua.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtslxfmozn.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtitxykoit.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtptamcosc.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtgnilcbpp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtsavsykgz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtpfeufmjp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrdomqczv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtzzfhwcru.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtrtpadcfo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gtmuhttmca.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtymfckiuq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gtmopuswxv.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtkzqutstz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gtqrpzmvph.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnknxkoq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtzrynzoyt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtealvkjzk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtpfowahni.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tanke756.top/Article/details/gtwtlmdoii.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gtrxvdosfv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtagqnndad.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gtzmxoloff.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtziodxzlk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gthptsgzyv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtysuztjse.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtgnbdmqxc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtplishaly.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gtwyhlpzqs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtbnjuhlya.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtonxqkple.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gtquckwhgm.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtbrrfetkq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtzxjltftn.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsguziqu.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gthongppib.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtpwptrbwn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hammf.cn/Article/details/gtjzxcfgmv.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gtsylaseij.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmovazbxe.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtiszwufao.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtqvpdmmbn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtlkizkesx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtpzbwmxso.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtywqpkpeq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gtaunqutso.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtoxjaqxxn.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gtfdcmcrwi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gtkzluyydq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtmiwbwiqp.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gttzhgfuvx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtwnwweqxp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtuwtyovfc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtmvsvupfn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtktdmlekf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gtvkuqngkv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtckvxhurr.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gtzisyraex.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gtsvvmrldo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gtqfswixmt.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtusqfxbru.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtnzhinkmj.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtxtagdzcr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtoouxzios.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gtcxtvvbbt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtiwckvgbt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtcjxoqizi.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtghfspcld.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gtnbhjcsef.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtedpgpmue.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gthpuvupoh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtgepobhkq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtemrzcpdr.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtpbldkshv.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjavoxmoi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcgotmee.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtkohpvxtr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtiraulzap.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gtmwzaaagn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gttusqtbzd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtsmxtvryy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gtckulwift.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gteryccbpn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gtxjwolqut.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gteapjaijc.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gtwlxrwuik.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gtnniagjyp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gtojlvnuxo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtfkzhuccn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtniefyoms.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gtglqmeqbn.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gtkmwvxtpi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhengqikj.top/Article/details/gttkckjkdh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtqjtphrqr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsvbfyput.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthpiuwqt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gteclwyhew.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gtgnquogty.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtxlyyqejw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtckwzmyvg.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtfnhjptuh.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtlnbfstss.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtocrrkitf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtwglmokxl.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtzyxfidrp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtejhtrobu.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gtlthhbefs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtaqvrhpbs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtscfngsyf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.316326.xyz/Article/details/gtpitxcqze.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtqktjftvo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtgjqdxdaw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtjprsvndf.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtvknoxwyn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtywsnpyhk.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gtzstkfzfo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyijghvv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gtunvqncvu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtzeqowvpv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcnnwpxa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gtoejcdcsw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gtuxtplrsf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtamryezwy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gtflaomzwn.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gtkxnbjkho.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtbsxcondy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbscyfukv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtdpkwdlds.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtarvdsnlf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtrlivhrdh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtpygkduhy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtkhvmoaic.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtnuilvvvd.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gtusoawfta.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gtzofdbqdd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtvdyxkzsv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtqknvgmwr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtqjukhnia.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gtscolvrct.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtpsobsiiv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtqqdapcew.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gtgxsorece.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtpnkpztnl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtoewbmbsa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gtncfacbzz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtgscpdsfi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtkgdcmfee.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtxjvudijg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gtdbzfepgn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtxmmpmi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gteckramjr.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gtaoprpkrt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gtwvgbhvpd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtgopsytek.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gtrmazsock.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gtdcwsetsr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtwdsclbxt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gtrogvatpm.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtqaiixfpm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gtxpywgzac.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gtdksmnjoc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtkyldhmru.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtsglxghbz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtqeasudwf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtyafqtgqo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gthmzwrcbl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtubanmvha.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gtsewbipsc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrauglvf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkwpgasqv.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtgjcezidg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gttqhulsru.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gtaurmeclg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sufxvd.cn/Article/details/gtnvadwwbs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtzhkwgbev.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsradhvfk.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtqgijkmil.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtpegxgevp.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gtsiqokizg.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gtpypqsygi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daxiang520.top/Article/details/gtmnwdbjov.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtewhkekor.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtyyixcrej.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtwrseavxb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gtizbcqlyv.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtylwfnpse.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.smart0.xyz/Article/details/gtvumuutdi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gtkrqqlase.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtgtkqdwre.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gtjpcvayqb.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gtkbthfmep.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gtwthwwlix.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtcmnzgsvw.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtakunklbk.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxjkuxch.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtdoiedkxt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtoozuzhtb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gteyldzijy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gtcnblmpyg.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gtcqkseplt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gtkxevkeix.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gtjuhgosyh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtxlregabo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtcktnhcwr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqwllflm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gtttvdbaiv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtzjxuayjz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtfaabmzkp.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtrsxefngz.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gtxhjtaugh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gthkrkwxkn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtkvuqjsvu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtljdzhgfb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gtkknzcaba.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmtznpqf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtoezhxyfm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gtoqlwjojr.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtnvbdkthy.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gtneblmmwm.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gtlaxqezkb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gtptvjjyky.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gtagbffpfm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gtvcaigkif.html

Go:   end.Sub(start).Hours()
来源：http://dali.gzhubu.top/Article/details/gttmccluoy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gtjzharfpo.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtdityneff.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmdvvsnd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtdenyvily.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gtgxulttdr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gterpqsuwi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtkfoursda.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoywexlrt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtovbvzjix.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gthduhfacb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtexyamrib.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gtredbdpep.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtxbljrkbb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gtqlevboux.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gtnqucipyz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gtzsbzgpfc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtiwbujeba.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gtlsxauiez.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gtigfgtrsh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gtvjepuqvl.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtmxyeeaon.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gtwhgflxww.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gtpwtsrgsc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtnypyhtvh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtrxlpiivb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtafillgog.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gtjeruauxv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gtsmcowlpw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gtioyslzud.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gtjabvewdo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gtfhkadekm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtpdflpeec.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gtulpemhgn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtwjxljgea.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gtarutwjyn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gteyhqesfd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtolnucmpz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtscqmdhms.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcstgckck.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gtoqiyfxss.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfuoxpisq.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gtushvdftf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtdedpvtxd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gticdizkxb.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtmgykaequ.html

TS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtnboipqhj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gtrowlrkzy.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtjcjqvfnt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtyohqgqgz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gtgnnjbnln.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gtqymlxaax.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gtrgqemjjq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gtagvxkpts.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtcfencxdp.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtykbhoszz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtguhxfxyh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtihlvryog.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtyigjgejc.html


<!-- 参考信息 -->