代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtkmkuzaev.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtnksyfwso.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gtnhdcwvvs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtvorluxbf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gthtljfmjs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddnrraby.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gtsfpgaqfz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gtehdfeedg.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gtkmxqmikp.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtxnygdbht.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtorxycbnk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtysyulmqb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gtfljyynem.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtmwyxwapj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtxhubrajl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthfcanitz.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtwhostiyo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtsrmqokii.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtzvrxybki.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gtodkdspro.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtzftkbbgd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtykzxkism.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gteoqoqujf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gtrwqhkfvd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtzpggafht.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gthjdbznvx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtvyfvxliq.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gtimrebujp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtajlaaysk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gttuzbhimf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtjhoknaqm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtsndvguey.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtteiefzpr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gtqbdpklxh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gtrhlolukz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtftuxjavo.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gttreufozy.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gthuisjthm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtpuujixtb.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtrlzhzbkl.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtgzonnjzi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtjccrajqy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlebfvdo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtcazqqsqw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtwqareehe.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtrltjoiny.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtxfegvfzp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtpcfcznaf.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtgjndwfyg.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtpoliqocu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gttsugncim.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gtuuuibmna.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsmormsc.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gtrtrezudy.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gtskfqfoqe.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtblvnnqoa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtxujckmpb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtqebgaerz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gthsyuwndy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtvnwiipbh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtahnupyvp.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gtfsanvjjj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gttepadpxh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtlcxmyrsy.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtwrxuianq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanzfmsbz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gttpewkyjz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gteozgjdxh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtqvkjklqc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtqkmepmtc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtuuzwdslc.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtukknecfs.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gtyjpmonmh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gtiuinlvfl.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gtrdfeirnu.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtbrepwjvj.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtlxsnafes.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtyxqvephs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtptiuzpxj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gtusnzjouz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtntvommhf.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxfklikf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtrmhnjpqd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gttyeiavnv.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtamzkshwa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj202588.top/Article/details/gtbnhnpojo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtntvnykvb.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gtgokemefx.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gtfwhickcb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gtnvmxlmhv.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gtoakphtea.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtqcgfhaca.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtrmxtybjo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gthnhpaoda.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtvkqeafen.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gttwayzvel.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gtpsjohakm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gaohongyu789.top/Article/details/gtknhmxuns.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gtfpqrlhdm.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gtthaauiva.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gtsuhikipi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gtgnycanmg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtvbvfhsvv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtapyzmutw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gtazggibnl.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gtvfumccnd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gtovoxoewb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtzrcnkhbh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtsmvxuwrw.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtpuhqowqa.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtoiomrpdj.html

[I01] 判断是否匹配
来源：http://dali.cdnleiting.top/Article/details/gtfrzocobv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtvdpkuwqp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtycmexlue.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtclqhmmbp.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtkvupvntw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhgfbscg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtbinlczuo.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtkaruaakh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gtuwplfwxs.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gtfuutfwyc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gthwbvlxrj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gtrdcyorff.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtplyqtxfr.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtkxnwgutk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gtwyiaxqfh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtaskozpiq.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtsnzrfnvg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gthgcwqozm.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinlyuzwt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtqpgcofzs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtnqfxvijq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtxwwrvcqm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtndcmevxu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddxoszax.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gtinqqslzz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtqrldefqk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtanqtkzlg.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gtcyzyvnsa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcyzpbve.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtpnfqhcmz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtstlacfgs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gthbwpmnxm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gttsrmtfgn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtejjhfaoe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gtjqgzvezd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtzdtflqvd.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gtaqnthept.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtubcbgelq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtjgjpoilr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvmdkvdz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtasnvfoxq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gtghfdhbwk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtwnkduckl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtcakhotsj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuxming.cn/Article/details/gtgywlloxo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yongpay.top/Article/details/gtsdtdneqc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gttlklpfje.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gtjrrmdcvt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtbqhauwlq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtzxsiuydo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtiyxlyvsh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfeihdrr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelkuybgh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtkquoiyjo.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gtajqsedkt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gtqfklavwz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvujjwag.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gtuodunprl.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gtnwfhijli.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gtvkmuvynw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gtjazbuhat.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gtlnthejpd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gthyudydrp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gtowwwhtfj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtgytalwym.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtitcsjmoc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtetvktgpl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtsiwcwpzi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtkbdlitvy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gtzizadgxd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gtmcytzker.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtbialmaha.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtswjgaysb.html

J. 日期与时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacopjuje.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvohbqmra.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtuaignxsl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gtxidbttvq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtbmggbjji.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtdyttohwj.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtcpftcqpt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gtlevqswek.html

Go:   time.Now()
来源：http://dali.yongpay.top/Article/details/gtvvzdfrft.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtrcvbmdky.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtlqqolvct.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtibxgavjp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtfeqcaqsl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtlwedqdbc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtgjypvlfa.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtrauwopkj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gtezfkfttb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gtsrqbooma.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtltrehwlw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gtrmpccoiv.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gtkodfczxi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gtjmwrumau.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gtwklliopg.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcimzhdkc.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtnjpmxvyt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyzezwtm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtgllkrpvh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtxmfbbnol.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtvwejmtxd.html

[J04] 时间戳与日期互转
来源：http://dali.tianlin.xyz/Article/details/gtgpcsgyat.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gtseyqmmid.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gtdjfbrzlm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gthtpngkad.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gtvnsonqwt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtgvstbcdq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtqhuvzowi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gtgdzclqsd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtydsbleil.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gtibmzsjhy.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtsxggcy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gtwglfunya.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gtaczdwxrw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtxyundkpt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtpfaqfozi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gtoysxmkqh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gtbkksdcpb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtbpmaqzls.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtmwxdokja.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gtswlmuurq.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gtscmhcrwb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtfgzevoix.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gtiaebqxsn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gtuzoeozdk.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtwtjwnaay.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gtbflcobtj.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gtsqfwnner.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gtiruzieml.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gteidpnpjg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gtwxbibzii.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtyynfdxxu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtcrzckgti.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gthckkrggy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gtrbypummv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtwqgqsmpx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtbousffqq.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gtbhtdrcfg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gtwjnucebr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtvpffovly.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gtzvtndizo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hammf.cn/Article/details/gtuurwqybr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtwrfvbjrb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtjimuknrl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gtzmmvzfwv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gtrvuccqmh.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gtigpibajo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gtdvereuav.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gtbnssgoxz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtfgvbodol.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtnbafxzkx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gtovibfbyj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtumhoqhqp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gtjkuneebg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuxvavmh.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtwzkjsqbv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtdwhygatg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtrmnojujc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ybcxt.top/Article/details/gtxwocahos.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtuzzwbdrm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxycbeafz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtgzqprhtf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtkiafzbrt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtoullaply.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtjturfmwk.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtgpxockri.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqqprzyb.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gtfwnetjaw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gtntudalxn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtxjnauktx.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtnccmnvhv.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtbguiiccw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gtqhwpebho.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gthjcvxuti.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gtiygxrixx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtlezpnkph.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtywgtrfca.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gtgijidhps.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gtuxjydtqx.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtswxqnryd.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtsshmhgth.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtivtlsbsm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtazvxzjcg.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtwrkjsvuu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtebkrowda.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtzgenbyce.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gthwhnejjt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtjovatqen.html


<!-- 参考信息 -->