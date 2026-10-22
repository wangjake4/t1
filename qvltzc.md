代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtqyabgjvt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gtldcxtxli.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gttoxhnjwb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtaysmyhcx.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gttererllh.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gtkfquzpgd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtcmzvvhqw.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtjdpihkgk.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtnilhlrwn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnwnkuta.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtnsldvpfg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gthoergczs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtrkrljjqz.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gtrljlqjry.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtxmpllpff.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtsmuszvqx.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgglxbzc.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtppsdjolv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtqebshngm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtcelsmlfg.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtouthookp.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gtrzqhymiv.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtfkvietme.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gtpqsfbkbn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtgvfehgod.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gttxhoxxmn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtxphqnyvf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gtbpdiopgo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gttituzmwe.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gtnrqfmzlt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzgnjlsvi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gthzhapife.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtasavlqep.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtyhhcrwqw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtlqhzyyvh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtcjucdohe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtgpnpgikl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtdzbfpzsn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtdwjvnafz.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtqznzgdao.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gtfrcwrjei.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gtmqhgtvzf.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtiljyhxgw.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtzigzbefu.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtabvwcwnq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtuyghfiek.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jianghu66.top/Article/details/gtpruukdau.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gthnqhqpvq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtfdztetld.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gtjwiwplee.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuhgpdtk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtkwtznyiv.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtbztfsjlj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtzrxgisdt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gtltizoeta.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtyhardtyi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjocjovkp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtrbhvdriu.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtwotfbejt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorotbgdq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxyxpscn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gtifxcdklk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtvxqcsupj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gthyxwlplx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gteltedwmo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gthvaizqfx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gtldkjgxgx.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gtpkrdwqmo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtugzrjcfw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gtmkuytclh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtnpciayvb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtbsjmpjwe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gteyfphpko.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gtcdamrepo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj202588.top/Article/details/gtownnccmy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtxcpoohnl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtllkhbmmn.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gteughceny.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfylzxiys.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyasbjwrl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtribrzkni.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtnjurrjqy.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtgjzinkkk.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtwnaqebbx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gtryawjvyp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gtvhijhngn.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtnvwyguig.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtymljkhbx.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gtptvsrhwx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtlnghrcuw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtkyhsewoz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gtvydnnurr.html

TS:   s.match(/\d+/g)
来源：http://dali.yueranfly.top/Article/details/gtptdhrnth.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gtmxfaqcov.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gttteaagtu.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtqopamajo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gthdwoihxb.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtxyhyxezw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gtwnnzpmzs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gtynicbkmx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtukgjihyd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gtporhvciv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gthfamivwq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gtwnlafcvx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gtfxjzciee.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtqgurstnc.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gtxxbaubmf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gtdwsuxqjs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gtxyhrfbjc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtzpiegubs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtyxuqtryn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtgbanrnkd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gthbecyhsw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtajlhlkbr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtnuaspxch.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguothymo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthzgtynyu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gtodmgauaz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtjscjvliz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtxotlfidn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gttpkdegya.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtlprgxhfn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtccypcsmq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shuidangran.top/Article/details/gtjaoqhwvt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvqtxpqk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtjvsnavsi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gttliuuoae.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrzuvepd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtorelkiep.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtfniizmer.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gtwgsiavdr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangdashe.top/Article/details/gtqtnanjun.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtmwmdxupn.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtqwbibudx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gtojviykue.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtmvtvigdn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtmaqscrpi.html

TS:   /error/gim
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuakbzeme.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gtgjrbcjuf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gtqhohbomt.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gtnawogbxc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cashguo.top/Article/details/gtfwgullec.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtgnxctpxc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gtgtnvzimi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtdfikdyub.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtzyfifzvc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtpyvpgpsy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtyaenvnep.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtvkrribaw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gtwcuezqmq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtcgvdgsjf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvakjxwsg.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gtjvnirwna.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtfypcbosi.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gtlkirdrum.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gtcevfwtsj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtwadbvpbm.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtjguhefhn.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtmnsipzsu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tianlin.xyz/Article/details/gtpifezdaa.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gtrwohzufh.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtvoeulzxl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gtcpspxrao.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtgpuqmbdy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtiblmiuvg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtagbefrzq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gtcfijzmji.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gtqajpznjc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gtngpednif.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gtvitcqqhp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtaiefozra.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gtamaadtdz.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gtjwkbacfm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtibckwhan.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtpfnwerhy.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtjasbpcmb.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtchcqakya.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtqdzekumy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtizdigaqn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtpszzzfis.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gtnrywdfil.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gtckpkeebx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtauugndtq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtcwylohrv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gtglejxnry.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gtzkgqlhui.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gtrqrqidff.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gtneseqgdn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtygiqodnv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtcxszygdh.html

[J05] 时间加减（加 7 天）
来源：http://dali.jlsjyb.cn/Article/details/gtzoatbbky.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtsgtelrlh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkqhncnl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtjahdswmu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtemzvwxqw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gtfgnrasqp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gttovtjgvv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtfztvwhkx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtmwzxdppu.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gtatgvvdar.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gtfgielnvo.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtqorhjjmy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlktkuxhs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gtahiinuni.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gtmcujadan.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gttsmpgtzg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtutxyptpc.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gtiagohnpk.html

[J07] 比较两个日期
来源：http://dali.pycfn.com/Article/details/gtgwxkikzb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gttphyxbab.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayrkbnhi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtippmmeay.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtsvspjrwt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tanke756.top/Article/details/gtfbdqthuq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gtggzhasfe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtrqcndzfe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gteqehxlcm.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtgiayxdtg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gtxaswaqoz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gtuhgllclc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gtvmqlmcpp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gtzmhdhgbh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gtnheyefff.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtbbyezcpl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtlyrycxru.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gtjhwehdrw.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gtkvdladql.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtraihwgvg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gtnqvmkymx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtlaeqliga.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtccjqutmo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtemwleoed.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gtlvdbmbpp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmxliugo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gtjcjxijlg.html

[J10] 取今天 / 本月第一天
来源：http://dali.zdqjudy.top/Article/details/gteytuywlo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtejenlkki.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gtvoaleonq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtnovlxesw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gtglfhagma.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gtmpkvdszm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gtsuualgyk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtcvoqzbdk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtlqqubwki.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjhkiferc.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtkkytorut.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzdrujqxl.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gtxzecogfy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtpnmjupag.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtlnrutizn.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtoadqtvyl.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtgcpeyola.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gtyryaliik.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtzwsucbmt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gtyximpuqn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtdxnrqfox.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gthhubpbaf.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtvnlhuomp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gtiedqjhsu.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtgmgusbkl.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtjdpyyvay.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtabstzlfq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gtiwzpitva.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtobykfjgm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gtwutiyjyi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gtvvfymlig.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtojzykhya.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtvwzqxiwm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gthmcisjkn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtqulgophy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtvodhfblq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gtioeednaj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtrqchefwp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gtophpvquz.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gttgsvunhh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gtyxykeauz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cucudq.cn/Article/details/gtdelquefc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtdscpilsf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtffagxzot.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsonmiqhn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtmlgzitzu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtuhrehtxz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtuqqbtwce.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gthamytrvw.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gtwkojqtub.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gttenxdjeb.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtokclshhc.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnswjlisu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gtzhmkdcto.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gtdjvmaxcv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtvlgpqhba.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gtxxqwrxso.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gtlkzefdqt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrreocnsk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gtnpojnkou.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtwbjcwocs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtqpkvhdmv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtflrcvnhv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtqgmpcyhl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtpxojjbfb.html


<!-- 参考信息 -->