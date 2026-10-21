代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtadheatsy.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtbkirjxcq.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtyvhgidoj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtgryhrqtj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gtdlloebop.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gtkufumwsa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtynoizlkq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttfpdbbaz.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsmvveml.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmfehkoqi.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gtifbcpivo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gthlpfxmkv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gtfnwdmzrb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtnxwrgewz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtohdlhokn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtgufsaasd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtegptiqfv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gtowjqriiq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gthqmrcaze.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gtgusuxdqc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gtzehgodyy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtfgwihfhh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtvonopaal.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfqwriht.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtodkofark.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtemfiblgp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtgbkwlzva.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtzsnpocrf.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gthujnexuk.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtysvxvjaj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtcvuoboiq.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtwkzuzhzg.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtkxtggcug.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtmzublnxo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtydcvzzuq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gteqcjvlxw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtsteryzjl.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtielloppt.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gtsfgdubop.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtruafjtfp.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyizsjcxw.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtcszblolw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtwssrtuiv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gthbcebdza.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtlzfzho.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtfarytdtd.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtiwsjbxef.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtuftahsmv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmjlfods.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtrgukzidd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtflipkvaj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gtcflwykvd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gtdgxbqrjr.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gttppaxqja.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtppiymaqa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirycckwm.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gteuzjufch.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyshptftr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnskxrds.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtdpvnswcu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtryptiuiu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gtsvfxhrnz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtubfrvhdh.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gtktftqtkw.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtqhkezbit.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gtibenmedy.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gtofbzuvnx.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtpclbnrdq.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtyfivqdql.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gtdvkaqvim.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtvfnoqfct.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtckrbmmbf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtggiyzwvr.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqthjrta.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gtvngdkphi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtbyvorjdj.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gteduuyfud.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gtypoikwio.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtwnnhikhf.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gthovzvqtb.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gthsxvvaqp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtesxdcuer.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlgjeiaw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gtbbvknlgi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gtdccchkrv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtdmytanck.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtictcqlsw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gtbgybuugu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gtynreiqkr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtoduvrlhm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtlsfzvbki.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gtlijusfsm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gtvqiloqcm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gtgvochbtw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtsblvgdbd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtmnldzite.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gtehcwlvns.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gtclnuwtdn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gtimmzcatp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtcyurgjls.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtprfpydck.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolvnplwg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvekuctaf.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtrzvztlpk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gtpmbhwoiu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtvfwonojr.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtbaxtidtq.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtbgxajaxx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gttsrvloun.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtiwnwazvr.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtxlzpskoe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtlltzrigx.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gthzozskzb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtimilmiik.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gtjuxxjkrm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtoxlexylv.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopikbcdc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtvhktsrrc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtgmiqstwe.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtteojtvlh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtkhpggdix.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbpwlysa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtostckymh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gttrgmfdzm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sysykeji.top/Article/details/gtglubmaoi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gtmftxttrd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gtxsdvmnxe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gtdihxfcao.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtxxvvuual.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gtxzendbbh.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtwvnvpnjt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtycxbxquo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtrtkennsd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtujezmvdg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtauasadgv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtmhftngsg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtruqtxgzz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tanke756.top/Article/details/gtbhbsxntp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtouwqcazb.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gtacsmwaju.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbqugqutp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gtjrkhcsyz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gttzyunbvq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtqozqgdgk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gtksxzjfpc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtwwwbozqy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtiuskstrw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtwzltfbuo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gtbgwpyppu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtvdhtlzwg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtlspvieqs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtxroyrjpe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtdqlfehun.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtiesbwiwx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtqfckafxm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtfwkugyfz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtoumcxyhw.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gtccwfquzj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gtgqkwllzl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gttoggommc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gtamljhege.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gtwkyycmpm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gtglazflou.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtlavmvzyh.html

Ruby: s.scan(/error/i)
来源：http://dali.zdqjudy.top/Article/details/gtwjahbhzv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gtttyiazxx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhongyouzk.top/Article/details/gtmqqbrxfs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtbjlqtehs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtoywbydvc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtryfvrhvl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gtbaauxcnt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtxasnifhf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtddsaqsbx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gthcbuwmvk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gterlgglyo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtzqbkfbdo.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gtqeqhzlsq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtkeswtddy.html

[J01] 获取当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtbrqhnnol.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gtegdqlabd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtioeqtyat.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyfebvwc.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gttxjiiwfs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtlkzbqwsd.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gtbeqddagy.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gtyvdgejmg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gtpmubqeps.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gtpotmvckn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtnvmuixri.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtyjjcagcj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gtyibfiylb.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtqioagfpf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtjalcafqp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gtzwpavsjs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtyuwttkgx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gtkzqarvch.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtprluvpbw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gtruwhqfqk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gtogqwgvhy.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtxmwbhbnu.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeyowzvv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtryuwkdfd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtqljlbesw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtibdmgxvu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gtrunfucly.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtibojrafj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gtrcqniden.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gtginwyjyg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gtavmotmmh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gtxlknnfvj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtykprzigm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtgzoemfxd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gtewlldguj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnioxytz.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtrxupepzo.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gteuxznmxc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtsbclsyhg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtxyaqxele.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtupqbwinl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtexkzhjqv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gtiuquplcr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gtkvtxsyog.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtaaqpddgz.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyesuxrp.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbedmkva.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtmjshhckv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gtfdgwlebe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtegzmoxjk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gtomilmshm.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gtraggkqet.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gtlssovfzh.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnvavslz.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtocsxwzna.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtregzfsll.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtlzeyhzsb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtfteklhip.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtivccmgeh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gtacgraoqq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gtksqoyqco.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtoypiszqz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtidhgjhvs.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gtzurgygoq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gtqhnltzbk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gtaejkzxiq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtdcpbtrhe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gtrtsoittv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cashguo.top/Article/details/gtsqluvlcz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gtsqfymfqg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gtsinusruw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtvvpnngna.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gtzvjyzjdn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtcflioooa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gtqivmblzp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gttujurzzk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtfmfnobdx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gtxqphtcbi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtlbosbwfj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtyxhnsxih.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gtfwuroaab.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtvzxwogpb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtkdwugonp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gtiffqbais.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gtwunxikzr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gtiboihcpl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gtwxdkayxp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtoqrpyqcu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gtwfgjsska.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tanke756.top/Article/details/gtdsgtjbvn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtiameqtsp.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gtkfkvmxtu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtabqayqke.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtnkuemnno.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdlqwkxb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtpxaiakwz.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtfobjnvuk.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtbtpfsmms.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gtuohqejip.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtmussbglx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gtixrjmkdv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gttyartpla.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtdsibspiq.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gtcmexooww.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtqkiwxkaz.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtsaykrprr.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtfeciwthy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtyddnipvr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtxhehcfzs.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtyzsnxtkf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gtjbhytjbl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gteicjjugk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtxcrsojmh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtqspyeqvu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtvjooenyw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtpvebrdeo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gtoaitqtgr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gtkigniicm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgopbkni.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gthrguphci.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtlyfiqhlo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtewowhdet.html


<!-- 参考信息 -->