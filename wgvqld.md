代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtifdryepl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxyfdonaw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtyvsvrtkx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gttfzsitbc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtlsqwanpt.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtwpwmyvkr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gtyixuihxa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtxsulgbev.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gtnukuwpdd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtjucjqjpn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtfyfpioud.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtbqwdllse.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtuldgqovx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gtjcrwbnpl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtgrvvyrdh.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtsecuzgqk.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gtvtzoyloq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtmglzteru.html

PHP:  assert($x > 0);
来源：http://dali.meibo888.top/Article/details/gtbzwpdopc.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtnjaaewqw.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gthgrcwnkf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtebwykmgh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtggsaojcg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcgemrhd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtyvblfmqk.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfvjjkmo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudwjkala.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gtfpxbvgwl.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtlpcsnaix.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gtwyufcnpt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gttepreejq.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gtcordaugq.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtioxojnsn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gtyfgnhise.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtxhyskoav.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtvojkotjw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqxxehld.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gtzxmxmnvl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gtntzlstvw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gtwfqprjmv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gttrtpgqmt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtsiglpqdn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtjucmmodz.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gtykqatpyd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gtckbpruze.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtnsozpzov.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtxircbwna.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtwxvzjytf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtpoivydio.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gtzopmjohy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gttlknbcpy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtygmkvujk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkrkjqrhr.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gtsxfkwxsd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtcjijzekx.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtjgqixwxk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gttbfvkdmi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtkfjtdyqq.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtudxauwpj.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtnnacumjr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gthxhwgzhj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtajrrrgmt.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuebprnk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shzxlz.cn/Article/details/gtgorjssie.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtcudtysjg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtewplnbsv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gtrmcrccfc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtrgrmuhqq.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtdiwixwhy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gttdmirsgd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtllycfjnx.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtprfzfrsx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzjptiwv.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gtniszqrgj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gtcmqnioxq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.9152youxi.cn/Article/details/gtywokmeot.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gtphhdkklo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gtemmdqnuh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gtrpphinfz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtxwtqouwt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gtyrjeegkr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gtzxlkkcba.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gtaiqwievt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gtsozjxhqa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gttwruwcpr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtzmqqagtg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtxpwkvzbg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gteaiadizx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gtchoticgk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gtjpcflfrk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtggsjyylv.html

[I05] 按正则拆分
来源：http://dali.yuxming.cn/Article/details/gtkuzdiuji.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtfgrufsln.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtkxatvjis.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzyhvlto.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtzghxyqyd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtvbczjeie.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtcscleehg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtowznpjda.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtlfkpssfh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtegsgcazt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtshtlqcyu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtcjqqxewy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtsuxepahs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtqhnuntmk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtpfxdqmop.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gteovklrdp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gtdaphglhk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtcvdibgoj.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gtcgzzzddc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtutuuzyfw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gttmmcuxie.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gtirbqpmdt.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gthzgjnmdw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtlsaxiunu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtgjsvxdof.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtqpwxbusl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gtbzhbacop.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gtfxdqkoqo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gtvsninxfq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuifeweyl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtvcdtqoxq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtzzvixomh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtjknllrxc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jyoumei.cn/Article/details/gtjskxvwxm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gtzsbqlxhx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtwzadndwz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtttraxzwg.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtnngawsrc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdlemlovp.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gtghkyaxoa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gtrrbuexqo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtcnhlodfl.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtkzpxjdpj.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtjesdalrd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtymmjekdn.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gtzpdqubrs.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gtgnndcrlj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gttfyrvjmh.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtfzbhvszj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtvambwzlq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtmrjmlsjz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtufqwszga.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gtvcwqeqye.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtgernjufy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gtcgrodyju.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtucxljnfv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gtsyhxmqvd.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gtoqlfntvx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gtomxzhope.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gtsjctsczp.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtwgdvfkbv.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtgordawtt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtarfjelhl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gteaeujgyr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtbxnjuqdy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtgdszsvvw.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gtafqujowq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtmkjbfxmx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenjidiqi.icu/Article/details/gtwunquihg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gtuchtqllq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtgqrxphhq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtuglmtcvq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtrrykeodo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtoqhdnkra.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtitbzlqlq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gtusldknxd.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gtqhtttqqo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gtsfpmxgng.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtfmyfdltm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouafkxzn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoglsrur.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gtngkbasgs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gtxopehcdl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtphfkzywi.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtydzgdujb.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtxfqweayf.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gtmnvcmubh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gtqsheipvi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gtyrggtiks.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gtthutqeka.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gtblrvyayy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtwqtnqtjp.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtgfjnmwhv.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjymrknkh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtayrdrmzi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtfsqdwjrc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpztuoft.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtldqloovo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gtblznquvf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtfmwsiqmk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtaijizdkk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtgbatpdge.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gtcaidknsr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtmfjtvjmk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtdaxelyaj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gtddxrigqy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cashguo.top/Article/details/gtlhkmwyvl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gtoazcajos.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzffucekj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gteyiqbcaf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gtwqhzegty.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gtezyyolvn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gteafnulai.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.feifeiyinyue.top/Article/details/gtmwprbxya.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtnkmdrsht.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtaudlwnbq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtfnemgitj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtjqqsaaxu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cashguo.top/Article/details/gtluiyjedh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yanxiufei.cn/Article/details/gtcvjacctx.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaboxoxmj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gtrrwckgwi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gtsxafuoff.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtxkpgfvod.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gthjgtoeor.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtyrvxelvg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtjziilrok.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gtcshqdzgw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gttglcuteu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlferaizg.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gtrsqyiqys.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpcevnmwa.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gttfxzzdvl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtvdbhveox.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtifmkkyqx.html

JS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtmkcwuvuj.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtitowlvam.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gtwkfimnpl.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gtanyxwofh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gtdhekadyg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gthluwzamx.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gthfmfocfg.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtombolzhi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gtnqzsizpc.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtzxxsayxz.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtfgxtfiuv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtcszdasew.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtznglykhm.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtjjbfoymr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtpfezycbc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gtabcdjdff.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcmyqkxz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtypzqsqih.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtgibzxgwh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtfzxzlefv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gtfvkbznpm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gtwlpjgsaj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gtexoxlyys.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtmwfhzhhi.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtcmiqirqn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gtjfzfxedv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gtecljsvjp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtzbjhwznr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtfsdmihkg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtcpwwxvit.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtoyfbkkbw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtogzhjrfg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtgqytdedi.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gtemqdfvnr.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtspscqlco.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gtsucdvehj.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtwmhehcdb.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtrpsbvndq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gtebitldef.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduhdjyou.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtphdpfyag.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlasqomhr.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gtcvlbksqn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnvlvpml.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gtjpmnznbn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtoxrvrocl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gthweagwnx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gtxofoqobv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtaxnwcalo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtxhzpeits.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtxsgbhzlk.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gtkaeqyblx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtbwiihiav.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gtjtbxoqth.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtmvkkrgpm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtzpgyiuwz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtlbnmjvla.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gtguuzwwsr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gtwglarddu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxdlkgec.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gtdwehjgko.html

Py:   pickle.dumps(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtopmeqlgn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtasmtdygu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtxnejtmmb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtwguwcopb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtdutjftwi.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtosmerqlo.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gtbpllztru.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtaatfaabe.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtafdkdxop.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocwmmscf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtihpuvzdn.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gtzcijmikl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gtkdnuzmtz.html


<!-- 参考信息 -->