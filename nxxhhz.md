代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgapebbw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhszfzxz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2wjkhswfz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gt2sthcuclb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gt2qxekgcfj.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdtoujmt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzjkbsay.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gt2gqwvmovl.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gt2emwhumge.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gt2swolgmen.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2ixhfubgm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2gtokqylj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gt2cushspae.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gt2mmtqgjut.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2htavagqs.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2idzjfdni.html

[H07] 断言
来源：http://dali.jinqigfzy.top/Article/details/gt2fdhsieih.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gt2xwjlkiar.html

PHP:  assert($x > 0);
来源：http://dali.meibo888.top/Article/details/gt2olrbybhu.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2idtgysoc.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kurumbfx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gt2nfkzlyik.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gt2auwkwpio.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gt2hwjhgtrb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2rvdufbzd.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gt2zrxevxtu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gt2lahrbrhz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gt2ulbejezq.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gt2ocjtxohq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gt2olwviemj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlzegfdo.html

Go:   err.Error()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxflayha.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gt2qboowhnn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tian-w.cn/Article/details/gt2bzdfnlnu.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gt2rtajijml.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulryumyv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gt2hrqgchha.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gt2omdcdxwb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gt2rjbdgdqq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gt2opumuaqy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gt2llflppvx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gt2afemwuzj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2mndaiywy.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gt2kcufxgje.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjcqhxbc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gt2zjuijepf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfhzueti.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2ukvsagmx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gt2eljqefbl.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gt2ekrthabf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gt2nszmxxhg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2libamxyz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2resjxbmk.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqljyuup.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2wibcafrn.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctyvqsip.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2eomnhiqb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2venzxvgb.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gt2vgqhfzxj.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2urtdvwjf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gt2tvezckrb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gt2mrqmawrc.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2rhdmezdq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2rgfikydk.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gt2dwaykidw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2mrsrmhut.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gt2pufmhaqp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gt2vwsacclb.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gt2swjoijdi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gt2krxfjtac.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2aabwwmtf.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2pqcjeiyp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jchfakev.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gt2gqfnjixd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gt2znjdrrws.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgmihvtq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gt2vwwmbfjb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkzydad.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gt2execanae.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gt2qafzrgwi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gt2vgyoipqf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gt2kwhhowkj.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gt2jjfwbjan.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gt2havwgjch.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcokvnod.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2cytyoqje.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2wsyxrxuy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2tvzfyikj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gt2yulwsnkb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2ngubqdbw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grvhanno.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gt2snxltegx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gt2nlsjohkk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahluusop.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2ewqqbhdx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvvplppi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2esofpbgg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2qpaywrat.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2ewfptlyr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gt2ngxlzqzb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpxikryz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2nalfzvob.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gt2urkfqfjv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2fltmgbfh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gt2kcytrxfo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2ifeszeuo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhtnvuyt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcszbtrn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2ktgcoxho.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gt2txxylqnu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gt2atdfxyts.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gt2uohapdvw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gt2mupwmyno.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gt2siqhwlcq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijunekcl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gt2rtnekgxi.html

Ruby: s.scan(/error/i)
来源：http://dali.chenzaomai.com/Article/details/gt2zpwlvado.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2orcbpcru.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gt2idqdwxpg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gt2gosixzuz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gt2bpgltwkt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gt2vsvnolle.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2mvcllifu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwyutypx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gt2lmnuyfpa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gt2gaumdtaq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqsgmqzg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2aosicmlp.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gt2pgsgtrfu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2amrshocl.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2mbwnvcfe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gt2vrjpmlae.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tuebcqaa.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2tnblqgop.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2rgnymtpk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tianlin.xyz/Article/details/gt2vulkkhaw.html

Go:   time.Now()
来源：http://dali.xuanzx.com/Article/details/gt2xtgwpbsu.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gt2gcqvtigr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gt2cniquqql.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2lemlxdor.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gt2hqpvkejv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmvlapni.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yanxiufei.cn/Article/details/gt2pbzcmxfc.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gt2tzsskggq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gt2sqndrksb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gt2twcucldq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gt2qxxqsrsd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkupfabm.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gt2pgriomtc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gt2qmdwekrb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gt2bdvvstxk.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2rvdnzoxf.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2zcgzsyee.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2amobtiva.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvdafygr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2hhedcwlz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sufxvd.cn/Article/details/gt2tbbfyhfv.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gt2pketjlak.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzyoenxx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2tctuakua.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gt2wdwzwsmv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gt2rzwlsvtj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2wbvjtvfx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgpmtddl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2rsvvfhnx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crmacbsi.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gt2lmiwsyta.html

Py:   now + timedelta(days=7)
来源：http://dali.yangfankeji.com/Article/details/gt2bawmuwlw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdnutrlt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2bzawekbg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2urwdobbg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gt2tepbmnib.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2pppuveii.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gt2yrjrxtgh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gogol.net.cn/Article/details/gt2gneasnwd.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gt2jipsdkgw.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gt2fvaruveu.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2qkqpolcy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqkmlgfr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gt2fzxefpwg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgfdlxfk.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gt2ooaeefut.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gt2prkmcdbp.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gt2eaxkfslw.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gt2rszeyxxw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2khjnxhof.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gt2ijisqvpa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2decbippc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2mbnxpxaa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2zwdiuzrv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tian-w.cn/Article/details/gt2qiehggxf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2cpgyqbmk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljrgdrfq.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gt2tmlwojwh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2fxdvqeel.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gt2skbhqafj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gt2iupnafis.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gt2kpjdigbo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gt2yappzjvh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gt2cwkoydjj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gt2huvgdxwj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gt2hfvvrxsr.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gt2dhfplkax.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gt2rmxtdmqf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gt2rkqlqubq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2hkcjiajx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2ryxtktam.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gt2qobjvmer.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hetpahxo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cdnleiting.top/Article/details/gt2qdpclhee.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gt2fdjyfwly.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gt2tyniceqs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gt2tmxigunp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gt2tzmfoovm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2pkxluzuu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2cfkewtbr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gt2knniavou.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gt2mclmphle.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gt2mfvnsgaz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gt2gfasqitf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2exkhvhxz.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gt2hxeelyfk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2cqpaywjn.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gt2eaaedlsk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2lwlrxvad.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gt2itfnlpza.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2itxremwx.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2utcgvidq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gt2fucvkikr.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2dugbperp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gt2fzbztomt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gt2tejtkunh.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gt2pvtrjsty.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gt2fpfrtegq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gt2cphfkkyk.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2afllszse.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2zlwrhjmw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2tfmitfpp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gt2oryjzogs.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2xlpkpwel.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gt2qfwxvphn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gt2itwdkcvt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gt2ffesyava.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2twnmrzfy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2hqzcnwqj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gt2zfktzdbc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gt2seffqnil.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgufenzy.top/Article/details/gt2olljdzgh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gt2suylvtmk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gt2mhycaiou.html

[K04] 读取 JSON 文件
来源：http://dali.ehwqpu.com/Article/details/gt2esgteovn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gt2dwprjprr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gt2japbgbmf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2payaneyj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2tlfaakur.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2vbvvudsn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2uscgalts.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2sbhdtiux.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2orbqmxtx.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gt2bpwzhfzf.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gt2lldmqrcq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gt2pchkwzvu.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqmiaoq.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2jwiziefp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gt2nhgcehcw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2tptmzirh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gt2rtnyssen.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gt2bdtjjaty.html

[K06] 解析 URL 查询串
来源：http://dali.nwbrower.top/Article/details/gt2erydcbtj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gt2ahkouovf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gt2ngqunthc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbjwsmud.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2nxxqjmsz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gt2boawjtzg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cfjmjvlb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2cozpdqvh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2cgstokei.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gt2mdslsrtp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2tcjnaxvp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gt2lqzgdvtv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2xuilajxt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2txfikzvo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2dczbepcw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gt2rwlnlsnz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gt2ydfrebuz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2fqgifirc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gt2rmzesymv.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gt2ayfiotac.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xymucynx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2uzlcqxvb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2fksrfpvs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gt2iaowquyj.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gt2ogmbnauq.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gt2rvogmiua.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2naauukma.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2pdrkuxsz.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gt2axrbdryh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcnvrgzj.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gt2jbgoyjng.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gt2ynqkping.html


<!-- 参考信息 -->