代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gtwuacaakf.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gtdbukdext.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtbsefxsar.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfvtjylka.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gtjwrcvdcn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtyocexmjo.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtybvonloe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gtcllnkxul.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gtplakijoo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtpptffvji.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtkjdjglvw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtwamjnkth.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.havefunace.top/Article/details/gtbxtirmtu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gtawynoxrv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtueivkpkj.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtiobkcjis.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtkdbsnlxs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtghjuppcw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtfyuzzzrm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdvtcmzs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gticxempns.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtxvozjvss.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtpgrxajnc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtnrinyczv.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtolzzmrxp.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtqcgnovmz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtkzqnliro.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtsryogfiv.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtotlqukqh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtkfjvotmk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gtmlezcbvx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtazdnhjax.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtbokdgxxo.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtjnhwcplg.html

Py:   class MyError(Exception): pass
来源：http://dali.sysykeji.top/Article/details/gtcreriiqo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtqwwmlaqu.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtmwiqpwjj.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtjhsbspds.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtwajplbsv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtmxxnwcog.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtaadsdksr.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gtzwaaitkf.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtlgkmrqco.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtvoqinqxs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtzngtwkfs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtibruasae.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gthvjatxyx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtubvccfso.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gtaidnivvd.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtbsbhvvxe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtfuqtaxeb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtamcforuc.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gtzgprpnna.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtvuxzksxa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtxvbjibwc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtfbtqzqvn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gttiudkiwx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtlzinkrba.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gtoexabyyc.html

C#:   obj?.A?.B ?? default
来源：http://dali.cucudq.cn/Article/details/gtwivbuyiv.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gtpnyakxmr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gtxqacldaj.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gtxdizbezt.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtrcdtrcep.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtmfczrzml.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtrifuuueo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtsinmvfvl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtcvfxjmlc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtksylsepo.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gtawuoaqvq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtodtmleys.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtubddtwra.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gtrqnaehhq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gteatctcet.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gtoxhepdhl.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtihbzfqre.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gtefczwrwe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gtgqfbkjyx.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtlxsiokgc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gtnshqigsv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gthypjyevy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gtyywwijxu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gtzhvvlqbn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtwtiskdif.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gtaspjjfqm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gtsrocvspj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtjxbgzacb.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtowfxgquh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gtahgjrwqz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gtxxttwgdu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtjowwugks.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtpxmsputk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtmnwridxo.html

Go:   defer f.Close()
来源：http://dali.zhengqikj.top/Article/details/gtcryxclse.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtwlusvlpg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtgyrbsjwv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtyqjnivte.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtfveiegtt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwwtyljal.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtbtgbtxzb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtmsylhrjw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtmvemazya.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtgffeikfq.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtidmhfpjz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gtpvmrovxz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gtjwviaivo.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtiizusmgq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gtrozgyhtg.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtfqdcjxhn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtnaxkdgew.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gtzeeupltx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gtpzemmbdz.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gtobprwzhq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtyjmokqfi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtjtlxntpc.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtxrnynsfy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cheryme.top/Article/details/gtwotuufaz.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gtadbmttoq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gtitbbosjp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cdnleiting.top/Article/details/gtjpyklodp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gtqputcygh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gtcsbfjler.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtyszjsruk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gtvbmghexj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gtehojjqks.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gtdfdofxoj.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtibcofdkf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gttrhuhted.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtjmjxwhzi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtdqugvdsc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtlkyeslth.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtegvamxec.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtxrcqjczn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyqtdjmc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtghpghugr.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gtrrziamwk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtwhrnyaed.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtifjtfdsd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gttwigzosl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtiirtiakc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yvedp.cn/Article/details/gtjavuzxoq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtrczlpgrt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtbzjdbvtl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtyxnkbtda.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtlxvtremw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmlxqxqd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gtusddgumr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzqcujhe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtjpuvwtfg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtortnmryd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtjotnvnil.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gthiktgbiv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtodjkdgfq.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtqbmimllk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtoamyiauo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtfuigjgwk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtvopuqvrp.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gthxuwyqpl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtnydzrrzp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gtzojwazud.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkywokeyq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gtnxvqupjm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtmvajwxvj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtjqrzagxp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtrjjzrsuv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtlvbopivs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtxvgwulan.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtyorpdwhb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gtvyvevidx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gtyilmedwq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtdhntmafe.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbpqipcqd.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtolofloox.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtasdgzslx.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtpdgbtrrd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtpeixyfdv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gthfptzguq.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtavzeqbxf.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtvqcozhhr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gtobwjbaey.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gtrrerhwsy.html

Ruby: Time.now
来源：http://dali.yongpay.top/Article/details/gtfagkhzbv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gtiudicrsh.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gthaqootpj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gteffvijzx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtscdmngoh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gtfmctppzv.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gtiyxvchij.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gtsirbegsq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gtigmctrhp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtttsfppgj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtuifbqugc.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtbbkksrtg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtkecehyma.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gticybxerb.html

JS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtwqqflzze.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtzmlyndbe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtuamlumxt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtijvlmsbc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gttexicfcr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gtmkoekhzr.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gtmjznlskc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtonyxvctw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyrihnad.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gtirypzfae.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gtnjkbrrik.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtzblnjznb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gtnekjvjog.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gthjapgcct.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtlnyfwyew.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtinemmpas.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gtezpwjikb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtrxgzvolh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtcjjpybid.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkmqrhat.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtfecfaoxv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gtmrbpulwd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gtgikkdkaf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gtesgufepx.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gtosglnxxr.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gtkcvqldwy.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtnfpwntid.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gtjicbtkmk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtjspifsrb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gtpztkkoko.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gthxcwkxpk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtejnzrauc.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtxdizevtr.html

[J07] 比较两个日期
来源：http://dali.xziqi.cn/Article/details/gtyjsqpftl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtvbjeryuz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gtxsyudlzp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtztyrakjo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtwinasqzz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gtwjpavdxy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gtsdlkhfed.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtounxenck.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtjavumjvz.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtzibyxpir.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gtrahngbxu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gtpdpknohj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gogol.net.cn/Article/details/gtmjquoiks.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gtpnbrqxra.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtxsybcaez.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gtuokqmfke.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtkjukuwks.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gttkbdzuic.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtedubpjxa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtneuphvbd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gtlwixwogv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtisgklgzj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtuwinswrs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gtsmcerjke.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gtdxrtgqpe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gtjoeumtlc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gtbdgqtlua.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtmucciqht.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gtxsbtsbhy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtujyxwbmm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gtrtqunjzv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtaqzwkejj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gtulqwuqnq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gtqgyecgam.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtkgonteln.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypisnqul.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzwqlnenx.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gtzonyxces.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtazqeoxop.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gtxnmygdwo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtpxfnvimr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtejfcpxfd.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtyiszapau.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtgnqvvigz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtkpwljucx.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gtrflsgjwx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gtouyotizc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gtasvszazr.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gtiwsigvzk.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gtzeujmwel.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hfpthk.cn/Article/details/gttvptgfcn.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gttieyqsrd.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtsredriyr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gtzkuwvnvs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtowulbmuh.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtmoniuosv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gtotgnbxrc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gtvyzldhku.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtnwvoioss.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtnsjjneag.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtrgnsoqqp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtxsdxevuz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtfttvihsa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gthhycziqe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtfrptiajm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gtdyxrnqiq.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gtilgrlair.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtbnntcoxx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gtnkoinhbf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtwhsdqcwg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtrxdgdnjk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtfgzcrohn.html


<!-- 参考信息 -->