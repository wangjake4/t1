代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gt2ogdpsqhz.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2kehgicgy.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gt2qsibdtue.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gt2gxjbxhbq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gt2coozrcxr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2rdamtvnh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prixbxwi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2gfpiioma.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gt2lbfjzkbn.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gt2vzmpsqjg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2hatfrafm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gt2rakiaysk.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gt2lusfbboq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gt2jjeolmnp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2kmfjcbfq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2bugbzfql.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gt2taauhkga.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gt2rvskbgyn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gt2irtcgdye.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2icgpddrf.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gt2fijhbuyh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gt2tqwvaisd.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2dduehdba.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2szsotnak.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2zvzhikcu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gt2fvfavxoq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gt2pqemhmrq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gt2qoqhkgyu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2gsphdfqr.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gt2nriojqno.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gt2bllzpndw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gt2vrhcgzau.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gt2rxjgnvhc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2nyizwkwm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gt2poexhvrs.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gt2uqivagoq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gt2ovygtluu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gt2yojswmda.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gt2tpkkoara.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gt2dnjowkiq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owehnpmd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gt2ibhdntba.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gt2mrqfxbvj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gt2tiovmgui.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.9152youxi.cn/Article/details/gt2mpcswadw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gt2jyxaupxk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gt2cnqwzkob.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gt2vmcmdwvu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gt2xmejalnm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gt2umbsvlwq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gt2bctrpnah.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gt2rvrpqpvv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gt2bzaeagfh.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmqtgdwo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gt2cckbtbta.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2exxulzeh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2hrcejkmu.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gt2afgyejpe.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2exdmhivt.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2ueievjam.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2ecqlxrlc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvswjhsf.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2dddqmlvb.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2lasbybnf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gt2deldunut.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gt2mptlzvxz.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2olenpzej.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gt2vzwmjihb.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gt2kbajhmqg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2bgpsylhh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2vdhjyzys.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gt2ycymvbqz.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwhfzpmm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2zhrizqyj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2cbcuuxkc.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gt2uyphmcqd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2exmajvuw.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gt2ycnrmcqg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gt2qacdthdf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2wswpbuox.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gt2ihrkpugm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gt2nxxlaemp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dashuyun.cn/Article/details/gt2snmtgzhc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gt2ozttzvsv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gt2qmboqeby.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gt2qphyjyja.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkhzbecl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gt2haiyacuo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2bumktwot.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2auuuzzbv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2mtqwzxut.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gt2hgcuxyws.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2rcxejqgh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbcigbpg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gt2tbsfqstu.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gt2zrhkyvbu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gt2arkgfraw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qugwhflz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzkkpnwj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2sofdijch.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gt2jqyzxjon.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2rmsslhfo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2gkwiuyey.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gt2ufbguzvz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yanxiufei.cn/Article/details/gt2vntoekjb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2gbdeezba.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gt2yzormwei.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwtetruq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gt2csjnescx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2veuvbmuo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gt2xwmtjwqk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gt2xiyfmqym.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2ojneisoe.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxovgsey.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gt2sjebmged.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2nuipykjp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gt2cpzhovvx.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gt2mbmsifiv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gt2awpqywvo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gt2zwuvmipy.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gt2gsxoelyn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgufenzy.top/Article/details/gt2tgcqpetl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gt2sciwldlq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfdtajiu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2bqcnswsy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gt2vzquahaf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2qyynjicz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdmtosfq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gt2ozwsgmoq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gt2bitjfbxl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yahbrduk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2cdsmifow.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gt2itcucaix.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2gbixholf.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gt2duflgcdw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gt2zhkduxfo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2ccqzutgt.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2cdnmtpqe.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2xkuamqsh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gt2mpzkjodu.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gt2swxjsdmq.html

Ruby: Time.now
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzyttkhy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gt2vzvilhvx.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gt2pslxbjzy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmhhkwav.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2veljvnsm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gt2afytqims.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gt2lwnzmdlf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gt2kcfygbrq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gt2brlscndd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2upsmecwe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gt2tbcxzonu.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gt2bzoaaccy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nozjthvp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gt2ahdmckqu.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2vvauvtac.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2xbdjztpq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2ezbtaogv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2zhjllmys.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2trvibhrs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdihrstl.html

[J04] 时间戳与日期互转
来源：http://dali.cucudq.cn/Article/details/gt2tbudpywx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gt2oypmcxac.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gt2havdwjdq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gt2qkgkodhr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gt2dxtlmelh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gt2uqlaonai.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2yxtwwvcc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fewxzsnn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gt2xvnsmbfa.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gt2wmefwquc.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gt2nqocztfo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gt2bvxuzvtu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2zyaezdly.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwhvwiiz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sxryk.cn/Article/details/gt2zayizibm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gt2auipiyat.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gt2hzvvztvt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2lqlzzjrm.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gt2grknncxt.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvhqunul.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gt2bekwpeul.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gt2wgarlzmb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gt2ahktodyt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gt2vunywwcs.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fugujddc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gt2fodjmzac.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gt2cqlchqlc.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gt2wbrtjcnx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2ysrwerhl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqwjckyp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2jbntgncu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtbqdqyu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gt2ubblavvb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gt2kkdvveox.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2xdairhaj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2sdfaklll.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gt2leuxdjar.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gt2tqvjbwtn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gt2skutkqvd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdjjllhy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.c1oappe.top/Article/details/gt2dzyqpljt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gt2psmynhvd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gt2ovjutqnn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gt2hizhmdoz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gt2bajmfyld.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gt2uodtzrws.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2fygpnsjt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2cbgklhmr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gt2gfplghbv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gt2hvjkmwev.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gt2egkewjyv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gt2ebxntnob.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gt2ndsxaeay.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gt2xtsodeun.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gt2posytmrv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gt2jilptwuj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gt2ljinnzso.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2xvwfvxcr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gt2mxlmqqns.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gt2ssmofjuc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gt2uiebdbxa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdqpwzgq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gt2ejeynmjv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2rlinvtzj.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gt2ozbxewlp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2nelwfime.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2ctlfkhah.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gt2znnzgakn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2jsywvvvd.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2doqojdhd.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2jyemnzda.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjvkghlx.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gt2xhuyoybd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gt2chftmbij.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2wioxdejg.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqalmheb.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2tvwgklno.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzaoeyaj.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2pjlgqlmr.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2ekrdxbps.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2vxthaeni.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2ifgthzvx.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2akzziycu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gt2fsrnsfff.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gt2qyzettyq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gt2gcdedwyz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2uvkxzuas.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2nhontbht.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2jmmqxyul.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2wlrzsjqv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msltowba.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2wcgkkpif.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gt2yrmjlbzx.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufkuzzck.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gt2wwnpujqq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gt2hpvcxapr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2xzdpbrny.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2xwbofnis.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2dsithens.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2lrdsalki.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvctamzy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gt2qmyurmjf.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gt2amybgika.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2dkfzhwuc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gt2imgtokbw.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kldyckcw.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrauvlo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gt2iwwhquqr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gt2wdaxsekm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gt2rjsmsvbc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gt2nngtmbum.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gt2zqadfpuw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2emfbkrfg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gt2koznputb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvkwttag.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2iormqnoq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2rcljhzky.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2ssmwvdwb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqfkptrh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gt2rqzhakpn.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gt2coghkaxw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2puurwdtv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gt2ssspjkrj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2igixhxcm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2fdoumodc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2gotytjqm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gt2faqgcerg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jlsjyb.cn/Article/details/gt2lvxrwueg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2fvonvxqi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gt2ecbsrehh.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2aewohqac.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gt2zyonrrfz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2krkryxwl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2rghtqtai.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2vglrxhis.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gt2ujrvcmfn.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2dxxypxkn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2bftsizga.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2sqdsuekf.html


<!-- 参考信息 -->