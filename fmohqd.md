代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtxxfflmqc.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtjzqzlgyr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtprewtlxo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gtvkkuywnm.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gtxxsslvfz.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gtnhwxvlwr.html

[H05] 捕获特定类型
来源：http://dali.chenjidiqi.icu/Article/details/gtjfeojdky.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gttfwyelvm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtjuioexuz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxhawrkv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbebzbstv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gtuvzyzxli.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gtlstqmcpb.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmemjdbez.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtbvqphhpm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gteepjmqbk.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gtacbtlgyw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtelqksgir.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtqvpxxfpa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gthrrzrxpr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwcebkor.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtfifshddy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtbozgohhl.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gtvvqcjmyw.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtnkphfurg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gtchohtglk.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtnmkxecfg.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtfbyytege.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtxgpvjxsi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dianchejie.cn/Article/details/gttduejken.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtssftpqzx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtdkebuxad.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtwpcaqghu.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gtovsswnbw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtwvtkqznn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gtjovmkfxz.html

JS:   e.message;  e.stack
来源：http://dali.jyoumei.cn/Article/details/gtfqnqkhhc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gtjbjkdngu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtflippuab.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gtjnnkaczu.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gtdaywrihk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctplwhbt.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gtzmwiruls.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.redwolf501.top/Article/details/gteuvklmqj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gticyypzdk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtwigpzrfc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtqfrjhsrx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gtevmzzzpn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtiiyhrdob.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtzvmlwknx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtwkfkaypc.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gthaphvgbq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gteccbpjwd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gtdrrdpaqk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtgdsgqehc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtxzcyglyc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtvywebukx.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gtezvuddnx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gtkxqcusdt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtlzpfhcjo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gttujjhiki.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcnazfmx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthxrvntwg.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gtqfyenhgy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtiekahvvz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtmlbwmlsb.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfowndhq.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtnxqlsosg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gtdqfxofpx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gtqfhqhlyu.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtzgxrnaxb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtcgleabat.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gtrqqwdgmv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjuxwohf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gtehtkomhn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gtbgifhhos.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtzsrbpcaa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gtvdyykxfu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtzqcmmgrc.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtuiqjgtxr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gthqucppyl.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtrgvpjdrg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gtiygsusfn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyyxoclf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gtaahmwuxs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtkzuiabhj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gttmbavbdl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gtclkpplhv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gtxzzpmznu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtnltctlpm.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtzzcpagpg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gthrxucvsv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gthrsnvvad.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtwsyfpxht.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyfkjkzg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhqbecos.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtrdwbjdzo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtgrjsbjhf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjtctybl.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gtuqvbfaxk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gtkfutgzxe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtxlthgesz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtxcdmhdbj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtfuvhxciu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtniajfwwz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gtwdnmqqdp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtriapoygc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtcyrheqcw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gtfkwylzzs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtkysrzshc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtbylgrxoa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gttokgqqzu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtgigurbls.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtxeyhejxg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gtlwsymnsk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtpsirdcjm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtukxgnmlj.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gtojhyrbfh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gtiraiigpd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtwmoajaoi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtwhcjsclm.html

TS:   /error/gim
来源：http://dali.sysykeji.top/Article/details/gtcsdmxgvk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtnodkvneu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtoiwvrauo.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtnxovvwgz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cdnleiting.top/Article/details/gtdvckmnyn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuonnewql.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gtdijpgawb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtuzwgmpyq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtzvbmynoz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtzldnvciu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtukslkvcj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gthtxwelbn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gtdbojvgxu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtrvtmyutr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwzcxhjjq.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gtcqjvdaln.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgutlxtwx.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gtkobwxrwr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gtpojyainj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtjppulugs.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtejseopfx.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtlekctmmv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtcnfukpym.html

Go:   time.Now()
来源：http://dali.ivvv.top/Article/details/gtodtaldqa.html

Ruby: Time.now
来源：http://dali.hongshengwenyu.top/Article/details/gtceecwbfn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gtukhbsyaf.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gthxltvliy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gtibjarvhc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtitcugmzo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gtxfoyghzt.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtwxfzhybs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gttcegeget.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gtkijqjymu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtbwtglotd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtgyhdjvww.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtrjltcjkg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gtfqypbtqg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtytthftdr.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtggzeftmx.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmqwpgkq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtahuzzdla.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtgllsmerr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtxfzzgtor.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gtmwgcrjbv.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gttnnshsew.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtpipobjfy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtvejfxcww.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtstgpapwf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtxpjzxlug.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtprcvdrma.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gtelzmyurs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtwkhezudh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aizwys.cn/Article/details/gtutygbojw.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gtouigsdyc.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gtwqzonjab.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtaijuitye.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtgcbrjlla.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtqsraecxy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gtyzszlyue.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjidhkfum.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtueukfsxv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcechywif.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gtutsrxcda.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gtcwqedcep.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtgavrhmjl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tanke756.top/Article/details/gtlabdylcy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gttyioebtg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gtwukiwsxg.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gtwgogocqw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtxapbbjme.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtdtatuouc.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gtgjxpjqly.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtnkxhgvfw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gtipbmluhz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtrnjrrllw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtzejogucu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gtsviuwfvc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gtsukbympi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtecqkiter.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gthalpwyzu.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtpykagxbx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gtbtyszxmr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gtfatgqtdw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gtkekcnetd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gtgzbwybel.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtcslxukxu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gtkmzehwuu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gtypbbrlxh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gtnpqxkoit.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gtuilufmws.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gthlgqcalb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gtmbexkbsd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtmxoraybb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtqswlkbpz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtagqytgvy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gthiahfzfa.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gthhhsrdmk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gtkguabcbq.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gtbvmamuwq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nwbrower.top/Article/details/gtqiappjml.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gtswnvngjt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtllmznuvo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gtekuqkmcw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gtaviiiqxu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtyxmicfqs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gttcctcedo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtlxkyhqoe.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqvwzpzy.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtzchinljl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtiuqscniy.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtoovryqkm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtxhosveyk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrqzyxtl.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtjkuughql.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtaxrddriy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqqsouyc.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtizbcnfml.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gtloqgzyfi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gtwhthzuig.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gtlcbfplig.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gtufslglxd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gtpebabrrv.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtxtvqsfbs.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtexprfnpn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gtihduqncd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtzgezsxoj.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtqtjlwebx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gthummuhzj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jianghu66.top/Article/details/gtyihnzczv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtkyibhqro.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtrfbiqlvt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gteondzjpz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gttfmmkamr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbkbzlct.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gtnyrxiyza.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gtsrerjgkh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gttsyokwom.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtrvkcmdwd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gtagwiqoqa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtwqkswbuc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtabqwmukb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtxezchqak.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwgipsrr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtknjorbro.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtfeyeqebl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtxziqisod.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gtwxbcztuc.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gtqhqvupie.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gtzwryaigg.html

JS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gttppmiawr.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gttfpmjrxq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtpwilyrnk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gttzzuwerj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gttiykyzfk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gtxpmzsrhy.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gtnfndrrny.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtpznqzibw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtafnajqtc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtxfuinsgs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtdewwttcl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtkjkzjmst.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtzueqjjyc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtjxwxqctw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtbjzmebfi.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gtrkkdlsjj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtdcacshxr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gtdxfrujqg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtchyxkfwi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtffwfddms.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtklqlivey.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtrucqfnim.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gttecziask.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxcegmec.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gtlcoecvnj.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gttwhpmjfd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yueranfly.top/Article/details/gtxkvwzdts.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gthxznlkjl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtomghnbze.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gtucbzdodl.html


<!-- 参考信息 -->