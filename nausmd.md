代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gtdxrltodj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtulwktfta.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtwwimmols.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtiaygbgog.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtfbjfoull.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtdpbfzghz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtthxiwvux.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtocbozwzy.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtsebxcrjp.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtdzxseyws.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gteerqdcih.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtsbmtpnym.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtomvblkis.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtlaqkaeaz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gtkpgjfhos.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtyxoifbml.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtlflngihw.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtqqmblolz.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gtzuxogjuz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtffjbvnxc.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtcxhrqesm.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtnqienije.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthggqrqgm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gtmbeloxcc.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gtlidxfupm.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gthvkphqqf.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gtymtkjhbv.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtygtksllg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtprblyvld.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtyoqkjwkv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtfiespsdc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gtdooedfbk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gttverwroy.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtownswmbo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtewxiwhti.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsstdwake.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gtdbrqrfbp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtzhbcxpma.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtwxncepdh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtmvqxyblw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gteoiixrap.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gtethpghgv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtfegclwys.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtjeygrqph.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtkwmkpway.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtsxjjqlfc.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtcylleorz.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtbhdgdvkk.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtwuktunoo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtgxowralb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gtjscgewrj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gthftigchq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtvruwdnad.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gttasesvwo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtcuzryhgd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtwyrdzzmu.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gtjpbtizoc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gtyhbdqdru.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gthhkjjrjq.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gtkbnoysly.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtexgdvzyp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gteuxsdbps.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gtcxsixsyu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtvuwjeuvw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtnvthfiqw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gtkxcibdhl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gtfwsruaio.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gthvhoagan.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gtwiskwpjb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gtylnxclmp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtbtdqnzld.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gtatiqshuo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gtugttteoa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gtxzkiyfty.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtdlbagzpp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtgzorvikf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtkifaendz.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gtgmdhxknp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gtdkkbewvy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtjzdfzsip.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtoqzdhmuf.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gtqtsmidun.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpsanwzsk.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtnwjklpaw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtwujyiirn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtpsrsbzhz.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtftywhrzf.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtvxboozgs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuxming.cn/Article/details/gtauyrsomt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gtjnqzlayk.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqonayjx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gttjwianrc.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gtiudkwhxw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtatlfecqc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtcjhgeojm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gtnhstmxkh.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gtapzvmdcm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gtnpqxswnk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gtyccolbpz.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtcynbkkak.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtdknxpmgt.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gtateitwac.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gtbnsvjeaa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gtyxxxcfhq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gtxwxugbdr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gttnzhaxaq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gtrgwuspum.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gtfbwvglbn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gtifravepf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gtcyoydkwg.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gthlhitmhh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtjsivsmkb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gtnvvbjuug.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtntlcpfkv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtknbtavpi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtmjgidjoe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtbawrbecq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtkjqsiyxg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtzaxdqhad.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gtqwwpmihz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtbgxxdlqg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtwgfirkkg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnvhfeim.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtjgnjwlcw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtwdizwejt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gttenqwcrk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtemkiyswj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtvrudywow.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fzhhl.top/Article/details/gttaydhvxf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtwqcxdhjg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gtcawvhyzq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtwhmwydqn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtuzlcleik.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtjadlvout.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yvedp.cn/Article/details/gtupxldkiw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtdpdbuyim.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtlcyfyaez.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gtyhvedljg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gtontcjxny.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjydjzcsi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtmzvznsgp.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gtcyjwaajh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gtzxsammzx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtobhfqeox.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtljqycuvf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gtnydnfmxv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gtagjmmvbw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gtsvkoqtot.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzlcexkg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtakmaanhx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtgvaquuup.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtvvqpzfwx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gtczlrcugz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtpgwbabpx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtjvpbnhcb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpvqajxjm.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gtjotlccxd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkftxxgpt.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuklzdmwl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gtlxaavssm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtqprixswp.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtoynqbxuu.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gtnburslui.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtnmplawtp.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtjpvszpma.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtpqhlxvbm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtjfyrrnlb.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtpkteqlyk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtyhjbapwp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtkdxmmcnd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gtthejhccf.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtohnwzpch.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gtrbbpuifx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gthxjcmaxb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtvxvcvgud.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gtppkmhitp.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gtakkfptjz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gtdexkhcgd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtwfonfgex.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtjgxukjec.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpywayqat.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtoevlvdgq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtasmxhztl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoncyvcf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtcjpmommd.html

[J04] 时间戳与日期互转
来源：http://dali.feifeiyinyue.top/Article/details/gtjfwffgaf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gtkzuqqtlr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gtpasgbqnn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gtpvzmawoc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuxming.cn/Article/details/gtjeipkfmu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtnxamafwj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtwhqgbijw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtkmodwbzs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtlfipmded.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtygnveghy.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gtmlsgeztr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gtnwxqppza.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gttizgbpse.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznnekkww.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtrlmyegxu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtigefcumn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tanke756.top/Article/details/gtxkhfiwup.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gtzjnyzemu.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gtchaognxm.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdknsivn.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gtmbfkxpuf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gttqjurtiz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gtjokdpofm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gtgboumrbh.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflghpatn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gtalsuhijo.html

C#:   (end - start).TotalSeconds
来源：http://dali.iojbl.cn/Article/details/gtueombwaf.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gtyvrifcwk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmcnrvzs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gtffykxkwe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtmyfwrddt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtsqtmaixa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gtyyeotjez.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtwoofpyyg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtbhngphsz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtfxrjjyua.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gtxumrlzio.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfazljtpi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daria6918.cn/Article/details/gtwzushgeb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gtpcbuaivf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtrwbbnsyx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gtubbvaeex.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtijaosczj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gthigbvbbk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gtqkoqtyci.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gtiyhlzfxg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtmaeuquag.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gtkymntbzy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtlkjvcllp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtqhcecwzh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gthvwoixhs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.havefunace.top/Article/details/gtgyvorpqz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gtqztcbkvq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtjldrdanx.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhnseacv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nwbrower.top/Article/details/gtemradlrp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfdcvusr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigmerlke.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gtzgovjwcb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtgkqryhph.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gtuipwuaaw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtopdnmjkp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqlfweyja.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtzsfxswcw.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtvrwntzch.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmhkkxecv.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gttwvzkvky.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtzhbijfjp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gttgqztyuu.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtqazwlvoq.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtslapgtgq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gtbmpuhqkd.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtmmngdkot.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gtwgrssnzg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtsojsbbis.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gtmuzciqsp.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gttozwgfaa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gtvxitzzmu.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gticvryabp.html

TS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtujhvtcaj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gtctdcxyqm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtzdpmnbvi.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtumjmorpt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtlfgazled.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtlgeduoaq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtiyparpiv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gtfqwvdlro.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtppyfjwbl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtjjmawbdp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtmmradmuj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gteqippunb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gtncvouzld.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigufen.top/Article/details/gtcpvzenki.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gtsmlqrzmq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gttvqfenka.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gtvkknzpbs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtbvdmndhd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtpavhlhcb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gtqnfjccut.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqthifqyn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gtykrhrkru.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtxhwdqkhk.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcxwomgm.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtomaazngw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtqbqaqyry.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtudwqptoh.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtwhxexxml.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gtghkkyiju.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexufblkb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gtvmbkmbbw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gtzhalwgkj.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gtfrzdfurp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtchxxqvkq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gtprfrsgaw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtawgvkbwx.html


<!-- 参考信息 -->