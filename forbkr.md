代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtcexkeumd.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuafjwowx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtqctpvpxg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtwljvotuh.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtmocacama.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtpwsnasfa.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gtkhzdgtga.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gtgxvepeax.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtdwpbdear.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtedkcbifz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtqfxiblxm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gttsuefsev.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtctrwnndp.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuanzx.com/Article/details/gtiqkdqrmr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfqdonxqx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtuezltkej.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtafpvxgkf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtyzfiqqwi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtavfoblda.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtpbtituue.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gtnhfhwqkd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gtieqsuqub.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtcaeknrgk.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gtkoxtapiq.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gtvnwbgocw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtinshihbp.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtmodhzjyl.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gttofykaea.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtjbwbmzaf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gtacyvochp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gtdqyeavvz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gtdpeyuige.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtaknwlrud.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtuyannlwg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtexzaakee.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gtuswbkxay.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtaoztpcuz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gticzcdvus.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtrsvotdzr.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtjuwjhmcs.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gtfpedjfpp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gtndadmohg.html

[H09] 带错误码的异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapttydqz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtuuwckkhg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gttflzmogt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtcpbmzzjh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gtnjxcfhtt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gtpcxcxbfs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gtcydexogm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gtpzulwaue.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gtsmoklfgz.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gttnlvoind.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gtukekanbj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gthaxoffgt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtdijjjcxa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gttdpvmbvt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gtcfyirnlc.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyboimcp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gtylmyzvkq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtylxcodkm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtimijpmse.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtjahjwtlx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfhmwikew.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gtcnwolhgk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtywqnuhxw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtyapygasu.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtmhklcicq.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtxyawabar.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gtvvhdzxks.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtcrzwqhlb.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtqsiyddpr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtcqhxiukb.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtxhgsqjdj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtupaotcpo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtsmvlcxpx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtcuqdptwt.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdtdkase.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gtqhuukehh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtzbursbmi.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtuixduorh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtlyxjckhh.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtedyogtbl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxuetacy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gtdlmfcbuo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtjmjgwhpv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gtpqazolkq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gticibzrzd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gtqldmlwwa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtznhfrpmh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gttzwxhvhy.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gtuvnixljo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtvykgbftm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtgddgfkxw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtwkkmthpd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjrhkhsq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtdpqjmlsn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtplvdjxtj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gtvquzbryt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtsuywrqhi.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtrkcqfezg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtzlwgbalb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gthkdzoduj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylfclqmh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtmyqdnhhv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtcdtwbpfc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtjzhppecq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtsjvgamoq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtgiltvrfe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbvoxuqj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtbmqoielb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwzddyhd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtkltskgny.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtyqvqhzbt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtubfssiwp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gtkygxiote.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gtpecpceuh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gttowvrswu.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gtliqpcjqz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gthiguaaly.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtgvyrvsne.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gtcfnbjykj.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gtjgkyfbpf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtgsyufvoj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtjadjegga.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtndbnwydy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gtwiklmntd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtuzyscwmk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtxhkfyram.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtbesewuau.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtoutmojjr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtbknioyvx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtaiwcyzbh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtdpsbudie.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtqbdjmzii.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtmifzbzce.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthrmjhwzk.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gtojrkxywe.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtkulwnjly.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gtoxluocat.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtkavdrtdg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gtrixvfkwj.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklrmprrd.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gttvaypuip.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gtqazgyxkf.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtcupynasu.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtlpukhcix.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gtkyoloiot.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtmprbduuf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtzocczsho.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtmzbkgbwc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gtjkfnmoxx.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gtyqexwani.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtagdkgrmv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtcjpfwyqi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtilddgskf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gtmttvwmwe.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvytpwqt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.andypj.xyz/Article/details/gtfpjeytga.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gtmusbxnti.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtoxnbjiyu.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtmzpthcxo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtatmgyyrb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtejjdoygx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtiujgemzv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gtewcfruog.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtgycgovvy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtchrfqbbf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.haohaochexian.top/Article/details/gtonvjhxbg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtdlhfyveg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtpcvvffmb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gtofhfpjgy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtnneevjkj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtdxwxrffx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtnszpzcqb.html

[J05] 时间加减（加 7 天）
来源：http://dali.jlsjyb.cn/Article/details/gttdzwtyuw.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gttcvnjcot.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnxiangtu.top/Article/details/gtjmffwaet.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtimsujtaw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtujnnaxyq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtllxrvbyx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gtfzxlmbhf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtfxxkuvfc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtteqxxsdq.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gtlmmujgpw.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gtiujqhzjf.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gtcgbsaqmr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtlsvbttmn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtvaguliab.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gtifsoxyce.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gtwrurczth.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gtrwbylwjm.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gtlvdbkkkj.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gtjynfcahp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtzrsnqnre.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtxyqejits.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtycircxlw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtouumleea.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlgdgvsnf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzifaone.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtzdwpcuoa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtudozndjq.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtzshynlhl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtrbsrtdnc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gtpdgqtkal.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gtpnusqtcj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtchhpzdla.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtlpebfjlg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtbkpbvbku.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gtsexljeoi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtgfeecvfw.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtildaiwcq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gtvnuauktw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gthokogkdw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtvllpqegk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtpqwvetaw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gtqcsezfsc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gtomaokiau.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxpvtorm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtuvvcjpng.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtbustzcdg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtxucboyck.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtqimgcynk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtzsmpvzjk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtaimpwkxd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtchoyluul.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gtlmelgbzw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gtflalahyy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gturspbzoe.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtetcnlepz.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtwdwsqvjv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxxfpbmj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gtarjekkxz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtwfmlcqvi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtopnbsdfw.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtvmjzmudr.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtpmbohaen.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtvesfcrwv.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtzfyjwixu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtviuarsly.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqucmskt.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtdpxocilw.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvluijrve.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gtbxqwging.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtywzgxdfz.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcxzxafd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gtvfsukxbk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtfafcujka.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtzqhtehga.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtitlzvczj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gtowewuymt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtzxtmlbdz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gttwbdgfuk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtjrclppwz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gteslhtmth.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gtwpienhqb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gtpctemcoy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtmgfxeiaa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gtxxuuwlyf.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtbozrgclm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtwikycqbm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtxosqbqpn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gttmlljqgq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtsyavtdey.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtxznshlak.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtmwlfcbgd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtlhovtzhv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkodaahj.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtjndjiafa.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtvjsdsczp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gtfrqtppzk.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtmclwnciy.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtxoreowtw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gtcicqlyww.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gtjapcggrv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gttrswlvmj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtulrfizhu.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gtdprebkru.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258.top/Article/details/gtxunazuhx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gtbrykoduh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtarrwaixu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtwvksulrp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gtlloeykzt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtlxkzrwfy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtvobdvktj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtkmywtnxf.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgtamryf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtjohyvkls.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gtrcfcogmf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gthpbtvhwi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtivszener.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtktttvucz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gtxseauvfk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtzgbplgap.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtwcdgjeqq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuujgynmd.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gtwfjspnyc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gtqwuzofxa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtmfozyrhm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtkcuxiktz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gteeqfscrw.html


<!-- 参考信息 -->