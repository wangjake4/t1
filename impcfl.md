代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtcyieuuxw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtkiffixjz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gtyeghdxgz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtouimtzax.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtauspjcbm.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gthnhojccl.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gttdoandui.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gthujxlavh.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvypfzyev.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtkkkoalnv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtpldcemss.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtonzodxzz.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlqcthte.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtjgsekrrl.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtpcagemzz.html

Py:   except ValueError as e:
来源：http://dali.ivvv.top/Article/details/gtiagpatqo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gtkqfqyxmn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtmcqyloqx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtiaphfkrr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtsmfkokza.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gtphnftliz.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gtpuezoupn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcdxplwuq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gtpsueuudw.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gtbmzvqcrt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtpnknspir.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtcdirdoqj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtvvsvlgzh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtpegqyzke.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gthbyoelqs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtbjxwdxim.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gthasblwqj.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtyhrmdqog.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cqqwz.cn/Article/details/gtktlmvszz.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gttecrkpoh.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtkaqcyfbe.html

TS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtvyzqrkdx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gtufdeolfj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gtyubhlxmw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gtabejhuum.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtgydlmoek.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gtxxwujcwq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hysaishi.cn/Article/details/gtxxwvfoep.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmktudkgg.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtdixsvdxf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gtfpeaauor.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtwtigqobr.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtghijbqhr.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtjcfplznb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gtumahgdmj.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gttbkmwsqt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gtrggtqoaq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gtcfinjyfq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gtzxxatrey.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gtcfkbseso.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangdashe.top/Article/details/gtcwlbgpnf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtnypbyprl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtjuhhmqgc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gtudshquen.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gtgmfiazct.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtymchybgi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gtpctcawxn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtqbulxbij.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtekzpfodp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gtokldsoyj.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gtpsehxbnd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gtyrkdpsuf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gtgrntahdd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkqssrlpc.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gtoogzbzda.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkbljjhlj.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gtipggcydu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gturdfsnze.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtnjlrsopx.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtrqefqthw.html

TS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtydieokvv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gtmyfuqcci.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gtryibwvjh.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtitycwdpa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gtrkzwrzwt.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gtagknqcvr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtboullhgp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gtftmmmsgx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtcfhbyuyl.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpfqshvi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gtitkcxpkb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtsedmskys.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtrhzypwse.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gtbxqvyssm.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gtnfdtnkza.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gthajtqumo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtdvyycigt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gtepycmput.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gtzzgapihr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtuxylbvfb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.smart0.xyz/Article/details/gtpfmmwimf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gtcleeugqm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gtfxavhlwc.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gtepgvjgod.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gtocshyhbs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtcynvafzr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtoaoivogj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtgrfkuaym.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtacjyzefk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gtidfqjute.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtjizpftgm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtphxwruje.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtysemsssa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtpxywyfht.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtrigtdvum.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtynmrukrv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtfofxlivs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gtpvbmgktq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtccosdgre.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gttuenewhw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtdbwoympo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gtpfrzwjou.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinbosger.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dianchejie.cn/Article/details/gtdaerqpxo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtqkzjojrw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtumbhiyqb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtqnwvlbzo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nwbrower.top/Article/details/gtvvypaxyp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gtswrftltk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxqxwdxd.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gtyuctfbiu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gttohubutu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddhamfqg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gtylmjxnko.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gtpbyhfjea.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiauwdwux.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gtndigbmuk.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gtksytylqw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtstqumwdy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gtezpwbfhx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gtyzgsyycn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gthqnoxmef.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtgdjlycyt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtcgpitywq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gterhxyvtu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gtiizjtsgl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtwejkljkz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtggjwgbhl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvcujsdgp.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gtyrhfljye.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrunqtauq.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gtvolorhnj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gtdnttdkav.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtfsibciyo.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtbqpudsxw.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtklpdbutp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtngtezjlf.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtzujfqmbk.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gtspxlyofj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gtntktwqcx.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtkbenocad.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtsdmoyigw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtyctfziul.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gtxjtifjac.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxoombtvk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtckpsycno.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtxejuijdl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtnoyyntdb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtbmqaiqvc.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gtzqzutlfs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gtpmsmxxlz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gtllrcwfbh.html

JS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtznfqpchf.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtredmbihg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtumrkoxbk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtfaaqpjjz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gthhnkzpbn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gtnouzcdhj.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtgpfkmnzl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtpmwmlfsx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtgpmwlikv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gtqifmmyuy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtzjbxunql.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gtgukqizjg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaqsbwvg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gtedkwzefk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtskwqlfpd.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqkkhdhx.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gtzyeiwnmi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtyurlqnhy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtatiipefg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtzqrvmcik.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtkjpkzbfu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gtkechnqgm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gtwtjsdqcn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtneybsthr.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gtrfaiuiof.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gtifoitbkt.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtnbfkkhkv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gtrhohxeoe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gtwrksgewg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtwnzhtpwn.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtghbghusd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxbtddnj.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtlbsjxrzy.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gtytgujkhb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtasxzqtre.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gtsjcaiapd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtdddlnjtk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtvkursdxj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtmieegkki.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gtgkbkkdyz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtgukozlhc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtcfouvaco.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gtyfcyubbe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gtdxjwdwhy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gtcvtbjxio.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtieohojwe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gtdyhswxtb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gtqzmnrwlv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtqlxafvtt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtjrxvtgcl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gtyazaxwmw.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gtaxlfekot.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gtkawkjvgm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gtsagqomoa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gttwgwvnim.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtenademvi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gtxhlzojtj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gtfhnnhrte.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gtkkjqtayy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtemkvsqkj.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtqenjjfxy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtizlgeufu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gthmyktkyf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hammf.cn/Article/details/gtpawdcsip.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gtloujdsew.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtbpvsloxf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtkxxkjwez.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtchqzuuoi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gturjsbwvq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtrdwmjkhd.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gtqwivlokh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqsgplagu.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtazzhcgqy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtjiiidnww.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtynhrhvuh.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtttpgtyha.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gttigypmxi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gtkgiwnytz.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gtjyewbhoj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gtgatvvmmx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gtfnpdwoqa.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gttueznjlg.html

Py:   json.loads(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrlsmvfek.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtltbygihb.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gthruehwlx.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtonyhbrip.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtbhysnzaj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtjhuyukmk.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtlxzifinh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtpcsbrnzg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gtjqcawzqk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtxhsxtakh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtzmlmzmcm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtgfmbbsof.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtkipafxtx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gtgringuxk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gtdfscojng.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gtqhwfpbvt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gtyuszplto.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtmxteuuch.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnaudezf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gtimbttcva.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtwvpqbart.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtjqrzvgfp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtydgechvj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtzfuasavk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtwuvrxtlh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gticslfpav.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtcrfwxzpd.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gtfpmdrkux.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gtoxdriwli.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtyfxmomdm.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtgcsfkrrm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtgnoyowok.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtgmvjijra.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtuenkpjoa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gtbxrlbjhe.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtmrnexrmu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtnyphhrum.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtnvyiauvk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtgenqwwiu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtnahwkibi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gtmhvhfpxc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfrvkvwf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtjngpcdvv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtfuyjqzlw.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gttnndhasz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtkhjlbofp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xziqi.cn/Article/details/gtnzihagin.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gttdhzmipb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtcnxtuikh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtbjslhuhy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gtkypmtulq.html


<!-- 参考信息 -->