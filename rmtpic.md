代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gt2pysuvxmj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gt2otulagcw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2gmliwlto.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2upvegsxg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gt2nbpdmhdm.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gt2czujhtia.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gt2hantopyp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gt2vgjnaxjf.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gt2veaknllt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjrwnjbj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2gwfvhclp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2bioijomf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gt2kxzpthxr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gt2ovzofcjn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gt2qrbakwdy.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2ulipqjrk.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gt2pefbugfz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gt2yikdpgbk.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mevelgax.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ydbxnctj.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2zvxyjoaz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gt2ionskxrs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gt2eerbqqmb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gt2siwcjipm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2sofowqgk.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gt2ccnspycp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gt2cquenoup.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gt2iwimnhao.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gt2pctgcefx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gt2hrudqybt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gt2orkdxesn.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gt2cooqcmcn.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdtwfpvb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gt2reewhssb.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gt2cuzxjkaf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gt2irhnnznw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gt2xhjausri.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gt2jngpmkue.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gt2wknpzmdf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gt2ntmzhqyg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gt2dgyyelnd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrzdieib.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gt2ccvrdctl.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gt2lshvcbqn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gt2tjinapei.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gt2poezawaz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gt2znsokass.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2aurmycup.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gt2ntygdbfg.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gt2nrqaeykq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gt2ydnxzecc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2ybssdbpw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gqumtvgv.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxkwxtmi.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2rwhhtiad.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2epdzcbck.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2hchkuyjt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2vzuhjmlt.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2yhtiwtme.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gt2qmbjiqcy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gt2esqbdilg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2phmrumam.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebnkmsck.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gt2evweeqjy.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncudomei.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrvcngjl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2hasxkzwq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gt2jkwwbeqw.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gt2pfavvvph.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gt2ylnfwrjz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2sebqsyhu.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2vslxfagj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2rkswrpup.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gt2sklojiyd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gt2uxdebbvn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2lyxemvay.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gt2uiuqncnp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gt2yjeyvjpl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gt2kfxhlawn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dianchejie.cn/Article/details/gt2himgxvyv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gt2msaaeidl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gt2igybifru.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gt2jsfwhqdm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gt2ypqalhrf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2xjqffpme.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gt2wkhwqhwf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2iqxfijgm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2hdtocazs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gt2elncdnsi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppmdtmby.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2uuebvgip.html

[I05] 按正则拆分
来源：http://dali.sufxvd.cn/Article/details/gt2lnvzrgzv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2mzsqxsju.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2sxsbpmef.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2msapjvrq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmbmnccw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yvedp.cn/Article/details/gt2sdlnlnfx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gt2omqehqjs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2ocdcccmi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gt2frgiglam.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gt2lhzazdfm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jiqyqydz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gt2nujejybd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2rohlilfm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2wrqqdblc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2olbkdrot.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gt2yheoeepk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gt2rgfkawfm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2mdkwfvlm.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gt2dwkxrtws.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gt2hsvwgalu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gt2nscmhizn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gt2kgnrxklf.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gt2cmaxhovz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gt2anfjagng.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gt2slglczig.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gt2jbdmnxaj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gt2ypxjwtja.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gt2lcjyjbfq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gt2xmmffhps.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2fssmimcz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2qiwyrubf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxjpmoa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gt2wytltzuk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gt2dedvcdol.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gt2wfawgynv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2ztbtikhf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2eydyarse.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gt2spupkwje.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2zdvxiech.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gt2hizzbqto.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2mqynavkk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2pwsyzghq.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gt2btsugews.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2knezvhle.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2nozdtbuq.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwtunxfb.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gt2lkisttvw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gt2jceqqtuy.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gt2dxluaqgz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2dpamsngw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2bixivbty.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gt2vhqtdsnx.html

TS:   d.toISOString()
来源：http://dali.mhx1999.top/Article/details/gt2ezkfxygt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.svipenyu.cn/Article/details/gt2jqzohumn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gt2rzvarmbd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2indmilhn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2nadhqeza.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gt2ljqbvfto.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gt2omjpvnhz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yvedp.cn/Article/details/gt2ybagtdzf.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjlevfzs.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2myilxzdl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2mvzucajl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydteiiph.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2nupsbypn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gt2wocazcbg.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gt2arkslabf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2iqusqimf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gt2liadkpgw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yonumen.top/Article/details/gt2xlgcakcq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2mivzjlti.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2bcnfiibg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gt2hwkxitwt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gt2bwvswmkz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzecjqt.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gt2bixsfzuw.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gt2mkwpxgis.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gt2jxbspjuw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvolbmd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gt2mtdojevo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2hqwwlghx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gt2wmftzloc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gt2ajevlgfj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gt2dwzknwot.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gt2miupgmrm.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gt2bghbjavx.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gt2fyrruihx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gt2wbhruiia.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cashguo.top/Article/details/gt2noseqerz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmorykgg.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gt2anjutpum.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gt2aoloicph.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gt2yithrkhg.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gt2uqewtoun.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2rwtwjgti.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gt2ruekgxni.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2hxzqfrxp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2pnrnxjvy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gt2tslsszsn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gt2ynrvfena.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2rgkftwno.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2fgjialcm.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gt2icxefify.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gt2axctbxmf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gt2gvvkakxl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gt2iwrzeakx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gt2drluufsw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gt2kcmqvyrq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gt2itpicikt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gt2sglgmhtz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gt2upzxryny.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gt2pbufyegb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gt2yrfeimqf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gt2vxmxxigp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gt2gpjocsuq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2bppdyxkt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gt2ftazhnri.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqpchpic.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gt2zduduyom.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gt2cytmumrg.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gt2dzocndxb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gt2qfwepuom.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.redwolf501.top/Article/details/gt2mrhrcari.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylyogtgj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gt2abcggdsc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gt2koohvbxc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gt2ycfqndax.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gt2qljxkded.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydlbtqke.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ckntfuwc.html

K. JSON 与序列化
来源：http://dali.yanxiufei.cn/Article/details/gt2edaqxfep.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2egyxkyww.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gt2kprrsiec.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2snanhrqb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2fvmkypkm.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2fcxalrbm.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2dpqsrtfk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gt2rogzfjdd.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2asrsnpnc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gt2ufmbhvxt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2lfwgwris.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gt2qcxmtdjq.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gt2kkegcnyo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gt2kyndxetw.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2xexujdqo.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2peyoyefa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvigbobf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gt2fogbnkei.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljumkefy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gt2wzefmodx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gt2bjbdzfwk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2fvsbeevz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2likeftgr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2vhqoxdsk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2vzxeslzt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vttzknda.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gt2kuvnphoq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gt2svievtqd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gt2iwwananl.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gt2onsfpegl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gt2fmvlzodm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqvkzsat.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gt2kujllpuu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gt2lhngeegi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2hofcmicq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdukcoxb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsdxdmmm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2whqdbvnz.html

[K05] 深拷贝对象
来源：http://dali.gzhubu.top/Article/details/gt2mledbhrl.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ojndfmgv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hopcqykf.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpchircd.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vsprlcku.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gt2thsejyrn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sffmbsfo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gt2payihzqz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gt2phosbyks.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfexzons.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gt2gjmvolyl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gt2juklqapi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2jaxezqql.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2fhwzqyql.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gt2zcbzvult.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2qpsnpblz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2vkwsriil.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2nsostovq.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2uklpuurq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2dowebwrs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2czbbfauw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2qczpfniw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2whfklhxm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2cppwcjbo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhfeedvf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gt2huogegqx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fitzvbby.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gt2colomqlm.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2pszhrodh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gt2hsrgsjnh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2fvsgjuta.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2sxzlhsyw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gt2yesccsit.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gt2czaicmzc.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihdldheh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gt2zzispvnc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2rrrvkmsa.html

L. 网络请求
来源：http://dali.svipenyu.cn/Article/details/gt2teggtnug.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2hooebhoa.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gt2ukjukqiu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylqkvvly.html


<!-- 参考信息 -->