代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtlxyeotlt.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvrtyghg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtjlgwsqlg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtimirnbmf.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gtrrpxcisy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtsgkbjkqk.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gtyccgwgpo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gtpgmccfne.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtwwhwxvrl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqtcxkzvu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtrwxyduzd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtscknpztx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtwdllmztl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtsuidhbcl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtdvnksksz.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gtoxmpvsdr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gtuwvzngok.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtpnltnntg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtxqomswwp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtmlxorigd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtfsuirpji.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtzdnxidtr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtedynyjou.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gttqvrekbw.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gttnhlczef.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcndxocgs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtbyolpazc.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiswxzxiz.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtfsoxhfdr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtsdemjnig.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtuihjnfjd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gtboicataz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtwkmreich.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygwnqkno.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gtniwwcgzp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtgjrpivsd.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtazcayfib.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtghujzomv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkkudbld.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gtwzyjriug.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtfuopqtqb.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gtkqoyacqt.html

[H05] 捕获特定类型
来源：http://dali.yanxiufei.cn/Article/details/gtsqhunrch.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgnwwsfn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtqnsgvemk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtskqicolq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtfcpvnqft.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gtekgzitcy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gtoywbyrqc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtpxwrkgds.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gtqifodxcg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gtbkdslvgr.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gtnplzxtrh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtdkioictt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtmfyxdkkd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtcbdtewzu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacpfzjdc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gtlynbptsw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gtbdgzhccj.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gtzxssokbn.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtaksbwnip.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gtjpbdtzto.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtkjzdmglt.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtyqaljcgr.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtisuxaidp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gtkysphobn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gtguyhaurj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gttlqabtyl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtevhltypw.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtawhjniso.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtwyqhiguy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmthhleh.html

JS:   e.message;  e.stack
来源：http://dali.jyoumei.cn/Article/details/gtqqfemctd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gtavzcyyws.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtjqryfrln.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtabdbnxzf.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gtvgyzqtut.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynvukzvs.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gtvhfaymog.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtsnhvdnix.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gtucuqdflq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtsjwgdtyu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtdpxrzgia.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndmwppza.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gtohprecyg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gtxnlbfoqs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtqwcgxhmt.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtquniyrda.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgziwntcf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gtyjpfemsy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtinuhfzoq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtradjqtif.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gtrzauemmr.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtlddrwyiu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtwlsshvzg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtxodmheii.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlhiqdqzw.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gturjesdsb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gteojkcmzo.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gtbopkodyi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gttzqsmvvm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtzgrhobax.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtbwvkauqg.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtfxpeqqpg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gtdjygqhrg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gttglvutnu.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtcowcfpfj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtkphsvncu.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gthqgacbxb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtajxhzjhx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gtvsxayetw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxpvpwih.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gtwsnjconl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtmficcakg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gtvviocjun.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtmydhowjf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gtzbjyzqer.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gtfphgdhrv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gtwhevlljp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gtxpljcumk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtdeugsrng.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtjvgsohgj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gtuwmofxpn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gttylowkgv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtmybthhfd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtwmnhskzk.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gtqepvoviw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwzdmkil.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gteujibhxv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtqwisifpx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtisejidja.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtqwxyefji.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gtycekabzp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gtsiitbzle.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtbzjdiuyg.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gttcerxzks.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.316326.xyz/Article/details/gthgwqqnpu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtqnsrasld.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtvqkvjice.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtttjfavxq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtpdqclcby.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdirjhnwz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtkefxtdqk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtxsvhxxho.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtuzdieyeh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtnttoippp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gtjdbqrjcc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtbpalyxpj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtrvyyoeys.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtcrqoinyi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtxaiobgtx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gtzvnijuzh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtgegolnhd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gtgzrkbfka.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gtjdzsvtwt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtmemvtwlc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtsgowxysh.html

TS:   /error/gim
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyfsgcoz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gtpsikajeh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtklmasnil.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gtvcbbfjgs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtpdskhapq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gtvzwxxbln.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gthphqcfjy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtfudzxvht.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtaeagmzhl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtjfecgxwb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtxaeboixb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtyokxcvun.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hywenlv.cn/Article/details/gtiwliqxge.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtqihoptgi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthhmxovfe.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtkligirsa.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfoaycpxc.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtyqnmdsvu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtnrpcxrko.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtvsxobsjf.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtkqyghezb.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gthuikurlq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gtdjhykmfo.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtbtthxuxv.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gtfypvzrkq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gtpobnices.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtwivlyftp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtvysmedxb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtejmwrsqi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gtrqjxutlb.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gtmtjeznbk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gtutvtavrq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtyxiofnyu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtsbcdpmnt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hfpthk.cn/Article/details/gtpcmwzybe.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gtclxcnanc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gthxdshdbu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgsqctlt.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtovboqndn.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtzotsvkyf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtjznydhsi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtmlcblreh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtbsyytnnv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gtgmylusuq.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtpridieuk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gtvfdhclno.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gtyvecsrql.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gtployhzgi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtbrxzpkrd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtafshcqai.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gtrxlesagb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gthnnicygr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtqwxirzzk.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gtdxtnnwrd.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gtlharixnh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gtxtearcci.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtilctcull.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtyiscendu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtelpksdbv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtxjatzfji.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gtzxpwyuzt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtkcxfkgsd.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gthlphvbhx.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gtibesboup.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gtllwmtwei.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtvsswvtmb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gtrwpgmsjp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gtorsirsih.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtitmklvcd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gtlvgvwtmr.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtgmwgitsv.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gtcayyieue.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtairydaqn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtkoyzngwc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtdchovmhi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtbfjvsaou.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gtsimnjxfo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gtpxubthzm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtysisvpsk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtumwdjywe.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtjajnuobr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gtlhxmytcb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gtdzgypdsu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gtgjjlsjxn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gtjfzbvnyp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gtatjrhopd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gtiuauqfzq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtzzrkwmih.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtfctnjcin.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtxzepdexn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtbferuqpc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gtmeentseb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtaifdzlex.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gthrjlyubq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gtoymuhuaw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gtgqaeewvg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtpzyvqbul.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gtkpqxuvek.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gtxoxlailp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gtwtqrmkjw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gtuirthmnk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtlckgboms.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtlwegagnf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtfiwfpzcy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtlvxsvygo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gturkvmspk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtwtooxhsy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgjujdosd.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gtzyneygya.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmpaorxsc.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gtmdbpojqs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtlqtirgln.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtggyfyzem.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtrxjtakut.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtpyohnxja.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gttksqkpwo.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gttycumpdn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gthvrsmumz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtitkmkaqj.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gtzhpmuqhv.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gttsjafqyn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gtsnacoxmy.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabjfmjsy.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtiaobital.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtaoszduqx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjvputxe.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gthvlwsxpy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtbydhoezc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gtqxjtfanb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtqlhbvnqj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtpxgnmugp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtpqcpquhq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtowvoxnnt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gtmactoqpl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gtusddpcyo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtrqxdagkx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gtmmzqwpte.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtmasliufu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gtujatccck.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gtkpdivqml.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtdkzrhcvw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzfnncyx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gthwrvknqn.html


<!-- 参考信息 -->