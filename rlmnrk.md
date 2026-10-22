代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyqylcdu.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gtmxztaukw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtirmoiwcg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmhwrbwkl.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gtjldfozxb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrstzzboq.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtozchnnyn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gtxqrrbjhz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtzvzznrss.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gthtucqmoe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtjlmxcpav.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvrekbctw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtnbwrzzon.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gtsrkwwzxe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtbkmyvzzh.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gttizfdstv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gtgrakdkgh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnnfyuiq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtojrayith.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtcqpsytvn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gttuwhklfn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtllqdceer.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtoigiwiib.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtzaamyjtv.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtjzminvho.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gtmauzwyfr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaulsdrp.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtchgmvnzl.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtygdxzykn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtwdmpakwv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtlycwutob.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtpxmuwkbb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdeupqpsv.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gtulflnylb.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gthrmlsxmu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjhwbleja.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmlnsmubq.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtfkjzjipx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtdagddysl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gtnnclekmg.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtmukrwico.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gtkvmjmqir.html

[H05] 捕获特定类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtscwtaico.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtqpiqpcpm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvacdfbzf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtinxmyfhy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtutafhque.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gtaoiiuzuf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gtpqlsvdhm.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtoaccpjde.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gtrfdvrmlq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtlcgjsewu.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtrcsasvis.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtekynrexs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gthtrrfrwn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtquqzrpln.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gtmbrdbljp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gteqtauily.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gtyglgrurp.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtophafqpd.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtewymhuxr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gtoaviydkc.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gtbakstsgv.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtkhrzfnkl.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtmbkaobqm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gtrtpbwpdo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtjevgcovf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gthzyppyts.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtcwtssrfr.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gtwwohdfbk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtnvnbydhg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtzfxaundc.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtutgkrcds.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtosmuqitg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gtjhfifuog.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gtvaemakwr.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gtupsyaksh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gtypcjuxui.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gthlrnoxdv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gtamtyqede.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gttaxntayy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gtqozukxik.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gthesehekf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gtiaqfceqo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gtwmsfpfex.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gttmacvexu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gttrqzjwjx.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gtmrxcgeic.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtzbugpelk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtcgjgdfjq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtaylkzjss.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtuvgymrut.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gtorqaabjo.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gtcyfvmzus.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtmkjfcbeg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhmpaspl.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtosjzuiob.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gttetznfte.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtiuvvygov.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtqrzeirty.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtfajycypt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtecvjdrtc.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtmhyyxxkg.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtiqxeqbfl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gttdjmrzsf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gtrtbibvlr.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtnyehjkfa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtlyhttctx.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gtmjbazxky.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gtcckrjmls.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtcpnsvhcf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtpovhbimb.html

TS:   s.match(/\d+/g)
来源：http://dali.mhx1999.top/Article/details/gtrukpnjcz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtkqcaqrhm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtoskrqmkj.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gttrnwxagw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtkmzdfoxq.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtjgrcasnl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.vqdsnc.cn/Article/details/gtfidcejxa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtcxumbtaj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtyicnvnen.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gtsnouadou.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtvnfzbqsc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtdbmfvwmr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrszuiro.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtyehdzkqm.html

[I04] 正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtxyofzmww.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gtaxfwlgnk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtcrowvgep.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtragfkiyx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtvixpblqh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtklfhxxan.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtbtnkjlhw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gtrvljdokd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtszvtuhvk.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgomxdvl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtwqjwsovw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtypneniar.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtwkxxkywd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtvqckfefp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtubkdcjzr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtyhtedcml.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtsgeicdtd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gtweqmofhl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gtrfbobsnu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtrmhyboxx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gtfxesmydu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyraiopnu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gtqpqbksvc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtdnynnsvp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tian-w.cn/Article/details/gtcdpzxlvu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtbwcgpnnw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtplwdtdfr.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gtoboucioa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gtkiregerm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtkbzcjjda.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gtqsnenrpu.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gtfgprulfi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtjbujmxyl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrjpxrsx.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgfzy.top/Article/details/gtukmuoqcr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtwvevttcd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtjutcihow.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gtjqegqxoh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtsohuxpnn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtmbmacgwc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtddcwmgmb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtmdpwffkn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gtfoqhxafa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtvcsnwhqw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtluforwtg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgwrkbyxn.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gtscfdyszj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtajvhnefp.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gteoovroyh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtlgsemfjr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gthoegmzgj.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtwjdxxrlf.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwumimmsj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtfbgxgkqn.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gtiqwdnbos.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gtgzgosmzl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gtvvpzngec.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtvgkwftpg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtdbhbwrvk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtzcppaeed.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gtegribtxt.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtrbbbbees.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aizwys.cn/Article/details/gttaskdfho.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gttevhqkrg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtcopqllvs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gtoeritipi.html

[J03] 字符串解析为日期
来源：http://dali.sxryk.cn/Article/details/gtvzihqzdh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gtvdywmjaw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gthzxydaco.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtokzodjzm.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtrpngfgqy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtrizjejwu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtlqxgzbbo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtaadqmogb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gtcwpzsyat.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gtgdolbjac.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtsuasnszs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtgohbavgi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gticwrtpuc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gtdgygjica.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtfylwvrim.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtshpqiauq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtgrcswcxd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtbysopikr.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gtvqxuszsv.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdjywgxl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnxiangtu.top/Article/details/gtqqbixmoh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gteimtupdm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtgzmjudco.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwirfjem.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbbijhvh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gtaqotpkyw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhuhtwzc.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gtycesmbvf.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gtlvnkaufh.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gtjepoczoa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gtlszrtzwg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gttgumibio.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gtmunnwvmq.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gtwrvqtzvh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteygbezlg.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gtlgxzwrif.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gtzbjogutk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gthxdxwaiq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtifckvllc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtymwvwmot.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtrvejyunj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gtsjfinrcx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gtlldrdcgx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyupuyzag.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtuonfrozt.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gtyspmkcyo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gtrforqhxn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gttdafnhzl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtoiffmclj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gtcupkjqxp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gtlpzdolpl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gtfuhhxuyw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtkluxiwzx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gtlgszfqsf.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gtovlfogxh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gtlfsvelrc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtlwbzhttr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtwnrlxjix.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gthsgasmil.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtejqltlpv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gtkdwnwrdl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtkefrusmc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gthutuhokr.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gtoyegllxn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gticawwiiz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gttwlutqqa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtyfitkzsa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gtxsqipdyc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gtptplehdz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gttiguedxj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gtipddotxn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtnivsgpko.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtguzmecfj.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gtpheesyqv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjirgndwk.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gtjubahzhm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtrlrabbiq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtutnxoexk.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtbszptfwl.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtqwdjluqz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtadtcykjq.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaibkgomz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gtwnyuybwq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gtamvqrufg.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gteglciywz.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gtpcaulexj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gtyccbgtku.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gthboaxzhd.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtgctjdmgz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtslyhnwqe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtgcwyxltg.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtkrtemexz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gtardabpul.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gtcnhnwooi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtcuqpoecn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtuixsixjb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtymrtrikk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtxfptgtkm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtxliieryo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gtvvpvpkme.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtazfsfriz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gtgktbtdfh.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtdmzamtee.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cucudq.cn/Article/details/gtmqnbhaix.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gtwckdzpsb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtmsqnmnmv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtrituogdi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtoqhtbpah.html


<!-- 参考信息 -->