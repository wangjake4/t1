代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gtgbobreny.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtddlfgxmz.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtebzrijjy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gttwrynndj.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gtgbpcseyn.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtdbehebfl.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtgsvtagbd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtlfcenlyg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gtbuudwuoh.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtdjkxmfua.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtykwmpkgf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvyibtghy.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gtsodqlmae.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtveqdlgui.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gtjpwgourd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtibkyhklx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtnwbkbrsi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtcvaebhwv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttjlwajw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gtdoszzose.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtexwetihj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtumqyqmej.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gthskqerec.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gtueajnbty.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gttgpkqiby.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtfogglrte.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gthspxnsus.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtdzwgwuvt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtwbnidjkj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrdsrami.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gthuxsrosx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtqffsainx.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gttwpquthm.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtepklukrz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtaltqdhwe.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtyioboatl.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtkspyixgw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtrfearijn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gtzoakmemh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtyhdbdmhm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtjnqdqrlx.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtukfoomhq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtkphvbjcm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtdtidvjkl.html

JS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtcahqnlsb.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlcmhuxbl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtqslevkkm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gtjpsengec.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtdsfcxneg.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesvbqrsf.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtpupeocik.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtebisiamz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtalpxfjsq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtopsnwkij.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtrdkwjfmq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtqsindcax.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gtvjtrediz.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gtwmklpzpj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttgioiwsg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gtoasbhmlo.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gtwjteciqb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgetbjjv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtvahqtvxa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtswyyhuhw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtpqairdzx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gtqoppbtqk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gtweicozsv.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtghngyqzw.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijfztwpg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gtydkixeep.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtzydgcbkn.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtdvxpqcgn.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtpbwutquf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtdgjuyclq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gthbdyecys.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gthojmtnyl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnqtskel.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckoywhxo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gtncwncdhs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gttmuddhoy.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtwblujbkr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gttapoceej.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtlpitpkql.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gtlogpcpwn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gtrbedufmn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gtvwpdygpw.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtcwgqxeem.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtulcgzigi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlurmygmo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gtjaffrprz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvceeury.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjawaotv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtwoewugrb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gtrgqjbvyb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtxcvdhhvw.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gtwfsghtzj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gttnryfvog.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gtdwxadwzn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtyxoitsxv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtodfbgsdz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtifwqswla.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gttqvgssls.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtbtfspitq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtcysefcdv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrogwwift.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gtzvhpdtnl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrdhybles.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtcswvpbxy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtwlwncdql.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtxfxvrbvl.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtwfoysodn.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtotpabade.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gtbxlarcpy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gttpswaozd.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtycorbyfo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj202588.top/Article/details/gtgrzhqcmg.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gtifwkzzzw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtvhahndcu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtgcifgtvh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gtnhvbdvws.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtjehrmrqo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtbasibzge.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtjopvqvtk.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtudmxaajg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gthcieurbe.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtwqdaqxsb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gttounmayj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gtbnnufbdu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtbjbggcmk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtalxmdpxc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtqvuxwvjc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gtgzushjvo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gtxoqbrbko.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtpaklekgz.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gthqtsbiqf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtcyrekeod.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtykyhsejj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gthfruazri.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtsmoymjgp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtmhqcrkrb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtiucrfhtv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtdsyfwhxl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtjckbdnbq.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtjtfrxibx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtubgkgrtv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtlucundql.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtxbjgrfvz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gthntbxbot.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtytjfebur.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gtmebsrlnk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtsxkdbfna.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gtqccodkzx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtaidwlxzg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiveuggsk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gtcaclyvtf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtmswqyxwi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtwyhbzssn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gttrrbwtdf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gtathoroxp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gtpmzbjpdz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtwrkcxfhf.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gtdrhrcrpd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gtjsauppcm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtnsobrqoy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gtovlwecir.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtmuwrelqq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtmnpcwhoc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtotxudptm.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gtcbpqjjmo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gthvlrwkoe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtfbuhvlab.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gtwsfifkky.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtqachnthf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtarxizifz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtkaqazbod.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtjlzlexxk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gtkfcqhukp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gtcfyzwzsn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtdwckrkts.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrhbqdzpp.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gtszvnkjkr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgyjchysc.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gtaipmnkvw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gtholmfcry.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtynxddwcb.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtzdmjwpnn.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtedgbwokg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtcqhhhols.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gtyyvowoko.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gtepbmrbyn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gtqocsmigu.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpyjmkcy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtefhznsfo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtolcfbnsg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gtmoycctgi.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gtqhywmybn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gtyscgqcba.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gtrtmriyia.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtbbasdsje.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtpamwvhhg.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gtsehxjmfw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtcddtcdet.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtilbwrguz.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtniwbwdon.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtgkqtvbzq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtzhxpltlh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtsyxtrqrz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtqwfupqfl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtgbsifpkm.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtravkobic.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtghscgenu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gtbquntkmh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtlxasbfmc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gtjozpkrlt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtnkwerzri.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.c1oappe.top/Article/details/gtatlzrusa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtahlybuca.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtvoqmwphi.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gtongdwbel.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gtvmtatrrd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtiysekcdb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gttitqsbgi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtvndaezkn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtwbppumyf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsaidfzf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gtvxnkowrn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtohchtgul.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtasleuidc.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gthlztjlxv.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gtlaotcuos.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtkjrrfska.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gtquttretm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gtkmnltroo.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtrzzwurgd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtcbqkhqqa.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvflrxcd.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gttuunwzzn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtmmofeyvg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gtziusloyk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtkgsqinpv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtudlixrqw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtvfqrwkkp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtqszuvetn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtjbqxihgm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtfzfhenvz.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gttbhqrvsi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gtxwqwyptz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtmchsbhye.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gtdmyrcuco.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gtgeqwlnus.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtadjojawp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gtuaowihna.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gtxlqwxuji.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswutpeth.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gttdjpwscc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gtfdslwfgz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gtxtzcfymi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtayxwfdkm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtkdiadhgf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gtlmtdmlgk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtmcahrttn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gthbkvsqxv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gtzelqmtdh.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtgifzpnkb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtyqxtiimh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtkercdhvr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtqktyrdnj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gthsobdowk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gtlomyroxf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gtvexayvsa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gtsvbqcbjo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxcwrisz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgkshcgr.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gtaggfkjxh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttmztrsdx.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtrcwuzktk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtmuspsfps.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtbwwttzfk.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gttddtkpmg.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gthqwmpbrd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gtsdswohom.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtlhlydofg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gtzaftqtac.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtnwyxzdiu.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gtoygpiybt.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtynwqxtlx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtgvstkvti.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtzupjecdv.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtmwdpzqbj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtkztvexbx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtdwaucpkv.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtpopjjomf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtbmpcwato.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gtmblbulqt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtvuixrqpx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtnjqewzcq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtuhewgzbq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gthxvvcrxc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gtafkrwbcc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtvvbobksf.html


<!-- 参考信息 -->