代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2ptbwoact.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gt2eofiakqw.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gt2xbvuexnb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gt2yokoiawo.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2cyijueiw.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gt2pitnvrol.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gt2zhrlaxoq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gt2sdvubsyo.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gt2xsntxplz.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gt2lurbuuii.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkzyuuqj.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gt2inexurjk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2dajwibni.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2blezfuns.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ooxyammn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gt2famqrzud.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqkodvge.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlfslho.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbtdxrgy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gt2ebfjfnnm.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gt2munduwza.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2llijkzgg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2cywogspi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2khutdfpr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gt2ixktubxq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gt2rjecoehy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gt2hyukdvbs.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2yabkqlja.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gt2grfqzhxm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gt2kntmuteg.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2xijucpby.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2gsivozmy.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2dwsbrmon.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sufxvd.cn/Article/details/gt2icebltaw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gt2zubrztel.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gt2zxhynoev.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2vqfscmvp.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gt2konjygeo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gt2tztgbchp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gt2jybxwszb.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gt2pvzyqrtr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gt2rsvqeyob.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gt2dnktlisq.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gt2szvclyhb.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gt2qvdfjjxz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gt2tnqlgabw.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gt2fqsvymrt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gt2xchzvvcx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gt2wzurfpad.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gt2egltygnd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gt2khlzxboq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkreubhk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gt2xnnxyqwt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gt2xlonricp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gt2tqyffujc.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gt2jzcisjlp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gt2oowjpils.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gt2wplhxhmd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gt2zzbkvwci.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gt2dgbynxuv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gt2lidsmtzb.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gt2vozcunze.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmkofbmz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2tnkeeysf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2tcconjap.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2nshodtds.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2zbczjfnj.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gt2pafrbezh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2cxksoxie.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2ergrgagu.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gt2wlyslfsc.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2pydssarx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gt2wrimjbot.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2mocficjb.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2nytkytgx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clwnuhcu.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovncavdf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgojxhcq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gt2fszrnufe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gt2tzfksqyf.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gt2norbmjru.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gt2riyygarc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2vjtqakbz.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gt2xlcghqfb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2plqaooky.html

[I03] 提取捕获分组
来源：http://dali.hnxiangtu.top/Article/details/gt2bloylrto.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ewufxzje.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.9152youxi.cn/Article/details/gt2kqewcejl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gt2fnttivpq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gt2xraorfqd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daxiang520.top/Article/details/gt2eqsuriqp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llfdtyvw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2jrvxxgae.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gt2mmwseyoq.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gt2mopijefy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gt2yxcyukvq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvxjictw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gt2kzmlelod.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gt2asbcddls.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckauzplq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2ykrofhde.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2hsegoguc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2grwrezkc.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gt2faayemzl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gt2kxqazibu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2dtdllwua.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2uxhkwelz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2ciyznvih.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gt2wzlbfubq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gt2peraqiql.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2vlioiltd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2qhytljni.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gt2emjycvmr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2tgochpce.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gt2nnqzpsxx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gt2vujnmxvs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gt2gponuntr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2ftszrrkt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gt2fntrndfa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gt2jprgjfgg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pheelezc.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlcetzux.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gt2mazkamms.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2faljanjp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gt2qhvcavom.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gt2ylyvjnjf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gt2ugrnjycc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gt2bmgkwkqb.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlcxsjuk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gt2pwvvepaw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gt2tnlrcchv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gt2pkkoesug.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2iqvvharh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gt2igqgwwkj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrbrxkju.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gt2jcqgcycl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gt2rjcvjtny.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgmjolbn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2pgconqwn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2kbltsfbn.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2twgxyofn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2whawobha.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gt2jzudiyfl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gt2oknysgez.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2pqgmygsk.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2urmmauwt.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gt2csurgemk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gt2tcabpzik.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gt2vrhjekkb.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gt2bcjkbgvz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gt2jteyoivh.html

[J02] 格式化输出
来源：http://dali.xziqi.cn/Article/details/gt2jimtykjy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucbvhgse.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2jhirntfv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gt2wfjvlfxi.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gt2hxextljs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gt2alxqrfmo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gt2okwbcwke.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2xlrruztn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gt2hnotfrzc.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gt2fzecscif.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gt2bafimqqd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigfzy.top/Article/details/gt2nemxtoxc.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2qwlgyvsk.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2dxfsogke.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2dgxbfhje.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2hcnqaybp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2cknmeibf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gt2uxyrejco.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gt2ssuovhgu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2qffqvhmh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gt2ekixbsfx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gt2ervlkody.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2jublikma.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gt2fijskcgv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2gnbbhrca.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2kyebixrg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcpeucku.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gt2iaystqrf.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gt2ailzhmft.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gt2xcrgcbpd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2vagbfkhb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gt2mdrzacmf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2kngfzova.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gt2uhdqatlf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gt2jdlbiprb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2ialiqbgg.html

[J06] 计算两时间之差
来源：http://dali.xylfe.cn/Article/details/gt2zmkpnwkv.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2jyvubnng.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gt2upbnarxa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gt2zssaismt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gt2lhdktige.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gt2xutrmwdj.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gt2hpbjsdfq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sxryk.cn/Article/details/gt2hpeydltm.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gt2itjzzkyi.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gt2cecssyph.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2wdapchdu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gt2dhiiugwc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdpamhyn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2dtaalnqh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gt2oqmudpuo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gt2jlchyjkw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gt2vuszdkja.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2lmsviduk.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gt2tunrxqgb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gt2qacxxvhx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gt2ahbfrsab.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gt2robwtoeg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gt2dpmvdzbx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gt2hncqxsme.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gt2sultgopf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gt2cetgytuc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gt2gnuakhqg.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfvamzrm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sowtqhve.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gt2lnlzbjok.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2xjvlasth.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2kwhpyjde.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gt2zkuavzed.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gt2mwpcytbo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gt2ludqdsdv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvdqrpxn.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gt2kiixijra.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gt2gqaujvdh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhzyggbz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uyrgjwlk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2qdlpsmpu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gt2tovemgrl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcmxucfj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gt2uffytzyv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2lyrzppwe.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ttlohsjy.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gt2tcwmoank.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ksxwkkdj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2oeutmsge.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gt2rtyhsxrc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2mwoyyfhj.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2kjqpsyvh.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2vavrgqkn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gt2khfxiula.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gt2gxyqszzw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gt2ppopywac.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2cxbdtetr.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gt2xrclgrzk.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gt2admqcqxp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gt2pcbupyuj.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2azeaouhb.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2eacxnild.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yonumen.top/Article/details/gt2xdeqsqks.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyhzzusj.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxunigdu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gt2brctdouz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gt2njowyryt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gt2isgzmxup.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2tqrdtsnd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2lbrctheb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2nbwypjsa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2zpmdaaxe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gt2kugxeqrc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gt2zhvufhqj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gt2uuwicmkt.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gt2fjxcvhvk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hysaishi.cn/Article/details/gt2ssoqffou.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gt2bbfpvjmx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2nkuoggaw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aueaachr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2exnhefjv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjradqxq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gt2hvgczwoa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2gdfzfpvr.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtwjxnez.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gt2yshzgrsd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gt2riuavzws.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2jzlabayt.html

TS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2dyammfhr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqmsiaga.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2nzykxtup.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcpdnpue.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gt2gfcntora.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gt2nwzdqjuo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2fumskhbp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aogwmzpm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2kjlonvdl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2pcvnjzyu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2qwzldiaw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2tjlittwm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2oslpemku.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2alocbbqf.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gt2dvmnefqt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2ptbdcldd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gt2zkggcnji.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2gwoxkhnm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2fqrvnjje.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2rpdvhpmw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gt2ckvmqdvf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gt2wttzrdyg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2thblkbqw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gt2rlfdplex.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gt2sppostuq.html


<!-- 参考信息 -->