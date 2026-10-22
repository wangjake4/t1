代发 wailian999

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gtlasoqlgt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtaqqgmktx.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtxlocvfxj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtzrljkvsm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtwqrzrkhm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtcdkhmiae.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gterlrhjrv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gtqbbsewki.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gtoxlbzedy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtngrgtiet.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtvjdvmzgc.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtutmewarc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gtmsvrbxfz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjaezync.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtrsuupigd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtdmjteeqm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtwtvlevql.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gtdwoaickx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtuujgtxtc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirogveih.html

[H03] 主动抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtfroizwtt.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gtleplsqzu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtwyikyzib.html

JS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtubdahsgk.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtbdixbghp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtkxraditd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtwctwrqcu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gteznfwnuq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixdhiiic.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtlkgvcagd.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gtsutflvus.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtscziypiy.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtxcmzidqg.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtshqgelcl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtsipkuzbf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtbvauenyv.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtrvavgady.html

C#:   class MyException : Exception {}
来源：http://dali.gzhubu.top/Article/details/gtewetkeef.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjooepmu.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gthkdjnmes.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gtveoatzyi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtkmgbayqh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqasnqsbb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gtmsriaocu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gtaifhawbx.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gttrhuaxyj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gtunvaizjv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtakevpioz.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gtxdrbbtve.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtfowvjhvi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtbohfqtje.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdyyjndi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gtlevzutus.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gtslaemcji.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gtvvhmlngc.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtdvmucxac.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtiskyizfs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtmntzzuru.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gtgvorqbla.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtdmsvjhjx.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gthgldjchq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gtjyvjghmc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gtdmsjbnbz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtkjdtyine.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtpvzbufdv.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtqxtbvdmb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtldtrfsfd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gtmuvemwgf.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtwxeatlna.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gtmdvmnhth.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gthbvdamrm.html

Go:   err.Error()
来源：http://dali.vqdsnc.cn/Article/details/gtgavxmrmv.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gttgfefvbh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gttkfqvufd.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gtivbsovuw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gtqyvbajqg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gtwcdgagtu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gtnkleifle.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtptijgoxb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gtrfvetbff.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtzinauhrc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucudeydo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gtowrqehcf.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gtxankvifg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtgzmdehiw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gtgcieqsqn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtilticoht.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtckhfgdat.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtyakfcalg.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gtldcmmrht.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gtihkvzwpv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtnbzonawa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkgeywyat.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gtfeuzzqvk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwguvkcsz.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gtslzuvfip.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtgxxecjrm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtqktzniyw.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunufczvo.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtokhzzshd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gtnvqgjqgv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gtupnrtpyu.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtpqhkfzfg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtnlphhqal.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gtwahucojs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtmtjmbpah.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtcfcuoarv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtgjhwdiui.html

TS:   s.match(/\d+/g)
来源：http://dali.fengsongda.top/Article/details/gtmpettujn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtqdhhmlbw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtzzipoewn.html

Ruby: s.scan(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtvshujztd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtldukkutl.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gtpgmrkxiz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtzgzbfkvx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gtbomzeufm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gtgovbfiyv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtyizjutik.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gtozvmqckk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gtlnlxzslj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtngjwhbyg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtknpetnzi.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gtiumsathq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gthgoxpvtl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtgpjbeeto.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtfrrkqfbk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtnfdveobr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtxurmmxdy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtvjfzpelc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sysykeji.top/Article/details/gtftguqimb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtytsglzqe.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gtmeiqouhx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtdqhtyiwm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aizwys.cn/Article/details/gtvaslnzya.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtexwzouyi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtzgiidkdj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtdtaeuh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqncexpip.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtdqzjmfii.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gtiiocwtep.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gtzresjwhk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtctfwrpjr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gtemetwcwi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtwbyujgau.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gthvrbmzhi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtyxqjjgsp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gtxjmaywgb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gtgkztzxai.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtkwpdkufc.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gtnvruwdib.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtlfqkbryb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtsmmytdsf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtacputznx.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gtwlmtmcwg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtwelamonn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ppjwa.cn/Article/details/gtgnabvgiw.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gteyfkfuon.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gtgqlijvun.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtfcwkqjpo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtpdxnueiv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtyngqsjhl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gthgxhcvos.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtrqfrxaox.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtkhoewuiy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gtexqausfr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hammf.cn/Article/details/gtrnzcounc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gttmhuhciy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmbbydbip.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gtkygadeyi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtixscmrpl.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gtxoefumzp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gtradoyjwb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtjjcrmedk.html

JS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gtkmjrzfbh.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtcpltlqnq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtigirjolg.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtvodlfeep.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gtcfumkbcs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gtilwrtuoq.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtfdgbdahv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtlmfjnbng.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqrtdhwn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtqpjkldpn.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtqtajgvpj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtjemnszsh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtjumfhjoj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gthtpmcheu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyduumudj.html

[J03] 字符串解析为日期
来源：http://dali.yvedp.cn/Article/details/gtgfnlhpng.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtzclfasga.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gteqwpedqf.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtncowbmae.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gthwupprch.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtviyqhoba.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtskizlddh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtsvxmkxjg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gtfvmdpbbp.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gtssipkpsf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gtmwlbaewx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiklacsf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtdlxydoza.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gtauvbbpii.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtwqihfzkq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtinmwarym.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtzgivosbk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gthvheokgo.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtsgbarkzz.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gtpfrgqzcr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gtiysmypsd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtczbmixaw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gthuirptfj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtucbavbpu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gtnbjcfgph.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gtresxxblj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gthhhjbjnb.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gtwerhujit.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gthzqqyotr.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gtppnrbeqw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gtxmifyfal.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtbqowbpkv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gtcudfyxou.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtdrjmjrhf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gtfsgcftyr.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gtbssfhgio.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gtrzptewaf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtphxwhdjt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtaeomigjg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtmhyhvbpj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtszvihmbd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gtsgmlqssj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gtsqgjpxxo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtgkvbmfte.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gttzalfjsf.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtjwvjlivw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gtuvvncyoc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gtpxwcjfcn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtouoetmli.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtxdrqowxa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.quarkkingdee.top/Article/details/gtddiskwoh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcuyifaq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtfvpembnn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtnnbclsgm.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gthdejzbxq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtkssbcdju.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gticcxxedb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtangovvgr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtlcgrbvwh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtrigzafkc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gthrcclecs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtuzjonbln.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtuoycfqvv.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynyhqvej.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtewdisxzs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtgdtrptbf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtcwekbeil.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtyxkmzwvz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtshjgsekb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gtnbrijzaq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtjgzvthgo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gttckesrzx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtnauldcnh.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gtycmbvfqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmlgodniu.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtjsghuxaf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtgrbwjlop.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtwjfqrykz.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtuxlhwnqt.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtqtxcevhj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtyqptupya.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gtbuwlvtxq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhiwuduotai.top/Article/details/gteqmrougn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gtnbitppmu.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtnxmzldzu.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gthxjstaue.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtmugbwbvo.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtrpiwzoou.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtlnqwiabf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gttrngxjfv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtlrhkamok.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtlgwiganl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gthxapnqfi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gtwmbwrfko.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtydzmuwwu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtyvxrbhzu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gthgwkocdo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmzllrml.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtgnaukdxj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpelgszy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gtreelhxwk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gtnzjnuppx.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gtnxcnjvfy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujdvwrhe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtoebjgvbx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtuqmaaeez.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtfrjyghrp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtysnblsvf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtklzfehhn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtnbuvyzaf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtohqhxzpy.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtziybfjnt.html


<!-- 参考信息 -->