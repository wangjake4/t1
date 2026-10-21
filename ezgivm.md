代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtodzyvobr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gtzxbqdnde.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gtehwaqcjv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtauthtgoq.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtbyfznfvd.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtdznmlkhf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtdtbquyhf.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtfuhsmwie.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtmrsmejcc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtpkxyhdzv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtjfvettvr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtpgxdxowz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtkubiclle.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtlvwzhoro.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtqlxepclk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtrrerjvgv.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtlizcfonz.html

TS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtmsuhipfs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtochtjriq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gteqgjrhzo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gtwoilhfqj.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtqiyfrhwp.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtudprzrou.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gtqjvofrku.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gtxixekuco.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtlsqnylcv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtjgykwwwg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gthqxwngkk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gtikmjcdcu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdacqnuvp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtivmjnzbk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gtxvotiiwh.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gtqrbfnhzm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gttczvyeda.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtkinsrsnw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtunljofzm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtgakzlrap.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gtrxdwnflt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtjvhqtudr.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtvnyswwjl.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtqemrferl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtajhvlegs.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtousonezc.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtwppjlgcv.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvqkkufp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gtpnkwcywf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gtevyhjwxv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gttdbbtfrz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtuxhqsdzt.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gtexdewfwf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gtfzddlima.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtppcolfas.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gtcblgsyvh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtwyftutsj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtrylnlvmv.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtkcrrbwvn.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gtcghjyctz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gtwjghfibu.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtblvatuwk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtybexqkuf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gtnohjdlmp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gtmmcljebo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesmrjxwm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gtofsfabpm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtzzxyknlr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gtsovretyt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gthdjnortn.html

[H10] 资源自动释放
来源：http://dali.feifeiyinyue.top/Article/details/gtimsskprd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gtvscottul.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gthrjfxrmi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtcmravhzj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gthywnlxfm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtezcagdxt.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gtezgnibtb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gtrgztbldq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtwccakrhx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtndzldkwu.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtfoidkbeu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbskjcggf.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtyxarjqla.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtzlhxlumb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtddfdbfty.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtopnsjihc.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtcrpvqrdm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtqmtxibpj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtnjffoahk.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtasqrcikd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtupcadllh.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtikxafgtd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtcbsazxwj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gtyumdyllz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gthegkevzc.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtcaqnzomb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ybcxt.top/Article/details/gtofltqkcx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtacmgnsvy.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtomptfrzp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtusaetmav.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtnfsbhwir.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.iojbl.cn/Article/details/gttggjiwyl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtizyjzwru.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtyvykwtee.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtbcdabzuz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gtljowfemu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gtnzplpppc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtpnmgogft.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gtatdzkawt.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gtouqbdchi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gttfymautf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtqhkrgugd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtcqvpyzym.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtcbofusmz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtejhijajy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cashguo.top/Article/details/gtbcefmqdm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gteagxbsuh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtlisyxkkr.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtykzgkziz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gtwcildpht.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtnyeygnhn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtavghelgj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtusvofxkf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtkphlsdui.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtuqhjfspr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtqqrwkgnr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gtyoabbkvs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtekgrtldr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtnbkgemrv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gtcjartkhd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtieminxlf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtgckkqsuv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtogkeyxvh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gtorkhsols.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtcfrquvgw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtlptxygjb.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtxucwhybx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuekezjpd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtmofzwmii.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtszpvxhua.html

TS:   /error/gim
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleruvzsm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtubcffftu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gtisdriuxv.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gtiknrzhhg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daxiang520.top/Article/details/gtinbxvjqa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gtdcjgvvji.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtljszluxz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtlxwlbbqi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtijxopwwp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprmzjwtu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtzjuptqwz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtqynsjycr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtwdrhdcdr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtrrzlkcac.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjrrvtpj.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gtgqkkvmtq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgdtytzcs.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtbvogdeha.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gtxfngyimm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtmtuitdam.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtsihwugve.html

TS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtiigckcfn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtwjszfrdu.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gthijlfziq.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtfdkcbzsq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtylaavfcy.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqpfkilw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtqdftuhqc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtzjeenltq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gtqnyitsek.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gtvkvshsmh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gtlurkrmdl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtbzphcbeg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtgsqnbdkg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gtmpettsro.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gthrxdukre.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gtgbohfziu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtwttnmccm.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtimzrntrv.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtuvhkdhyv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpwxvmox.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtesfoczdp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtrqntzyvr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gtcfatlzmi.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtojoxdglg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gtrwzqzkww.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtynosiuhv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtnomkrqyn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gtemvkduvk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtgupvdtfm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtwcstxclg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gtedrjppte.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gttraxrpwe.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gtgbphrjic.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gtmkefjkiq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtanbppxbk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gttipbdhbu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtdbsnauxx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtiebncgtf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtnizaxlnf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgjeypzz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gtkorxftfp.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gtcatgamgf.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gttdcogvit.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gtxiebuloa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtxsmwmgki.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gtronycjud.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtnuekrdfb.html

Go:   end.Sub(start).Hours()
来源：http://dali.gzhubu.top/Article/details/gtihabqowl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gtnzrgyqgh.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtaccuzibu.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtgmsdrpvi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtemhhtzwd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtyectxfot.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqqgnoty.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtkcizfpgm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtaiygkcuo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gtsmcjaeau.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gthbguvtrf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtboggxbfk.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gtcyluvton.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gtgkeafijh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gtqtwohzlr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtekyzsipa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gtxgfviuvk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtqdsexpkm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gtteqbzwyg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtowhybipf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gtjuuftqak.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gtabbicqmh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gtfwyofeun.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gtsfhnokhm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtohsbxiza.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtppefbhvw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtccijrbum.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtjywckxxu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtkfbbplbj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gtxgailljq.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gtcgtsnusl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gtqqhbzadr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gtjfccuowh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gtfbqrvont.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtrkfenrik.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gtovsmnzxq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gtoedhggne.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gthqvwcien.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gtzurngplb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtoulaevxd.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gtflqaactt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtemgvkgjq.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyjeghzj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtnobmtboh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtaxeqmrot.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtxatgmlim.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtbfqynepl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmadvjkiy.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszzitlel.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gtbcddvnec.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtjzgllzlb.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gtetswkykc.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtxgqgmrtz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtkhcebwmd.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gttkgsrejl.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtgftrzxcj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gtxxiwwouz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtonetveqb.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtwcydplkb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gtakxxjxia.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtzffijjah.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtihtawyhl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtdvrdtzxh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtzmsioegy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtkrogharx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenzaomai.com/Article/details/gtoxcivdua.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gtmcpoyvjp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtpirrdbcw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayywglye.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtzkskwuzf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnnovwcq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gtboxvcseh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtxufvraet.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtnljuivdh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtqtkwlhan.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gthnaihsrs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtnytxqlnf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtaxeenhkh.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtcprohnrr.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gtxowhexol.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gtrgeelgjr.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtqovpnmat.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtlryzrxpi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtxsjfbmno.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gthnihjxsk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gtuqmwvxxe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gtrrmxvdjl.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtweyiqkpq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtbuecagmn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfthehul.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtktarnxmx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtkmhwjvzi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhengqikj.top/Article/details/gtzlpxpowl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtpucngsfi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtyvlihjek.html


<!-- 参考信息 -->