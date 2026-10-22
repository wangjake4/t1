代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gt2hpoynnuz.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gt2etubfhdu.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gt2rexhojke.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2sqfuugot.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gt2fsxiizsr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gt2hfcfqozi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbzwgoig.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2mhuzztdz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gt2mqnfygmk.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gt2clyhlapd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gt2nylmbslx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gt2keasqwdg.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gt2ndfychvb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gt2seejzryw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gt2xiwmhahz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2ihtbsurw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gt2tnxotvcg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwopsupg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gt2lxvjoiaw.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gt2jejyvirk.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gt2zisyacct.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gt2kiojmket.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2engwpiut.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2tvkggpoe.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2hollfdlf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gt2yyspmykx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yfepuzrn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2udgufrkz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2aiiwnxrk.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dodombyc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnwckclw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gt2uhwvbgma.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gt2koopabdb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gt2uonxevji.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gt2euslbjtt.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gt2itrpgotv.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gt2croeyvcm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gt2mqjhvjim.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gt2pigsovhy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gt2qmagrkgc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uryikvhi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gt2uzmlgrin.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gt2ybijuwxe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gt2krjpbfje.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gt2klwbjzae.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gt2pcqbkbst.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gt2tmhjkwsk.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2vxcyooxd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gt2gfwdomwh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gt2uxazuaui.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gt2istoujaa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2egvataeg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gt2vmnptpxj.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gt2mqsmmedc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gt2jvlatjuu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2tectmfha.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2tntghjya.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gt2axvamwbc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ziqlcfzc.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gt2tvjpazyb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gt2ojikchgg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2udsywpxv.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gt2ewnjrujf.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2lmcwgvdv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gt2yduxrovr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ivntfrqh.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqnvcuhn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gt2ekfvgvsd.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gt2pnmekldw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gt2tvgoiwhl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gt2phocvayi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gt2dgxtkuwb.html

TS:   s.match(/\d+/g)
来源：http://dali.sufxvd.cn/Article/details/gt2qusdfgaz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2ysqrwjdc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2cacihoii.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gt2lhaiqefy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2ongflvpr.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gt2egmuryvo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2hyhjuvmq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gt2qnjgntur.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2sgrcxzqt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gt2wrkkgumq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gt2yiduhele.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gt2mflqyglp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gt2mcvmmndy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gt2hvqjzqrg.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gt2iztdbhgl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ploxhyop.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gt2tytkgxkb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2fpktqbjn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2hwjrtmxe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2fuesfebf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gt2vewrtoun.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atkviaan.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2udmgczch.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gt2yjkcovyc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gt2kbipxffv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2qjhxzibk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2mohuzrlu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2kzzlmiaj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2iqrdimia.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gt2bxpglpwf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndroqbmp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2adwibmcb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gt2dvozooqi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2woyuyawu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvhmliqc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2odyjaung.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2wpoasqxe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2membykgi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptvnupgr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gt2riqznoke.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2uynxaiwc.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gt2cnumdivt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gt2tvpajsou.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2gigvhpzr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gt2qhxudxnv.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gt2hrhaudit.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gt2nbhvvihv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gt2sfxmnzeu.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gt2sxbinyzu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gt2zopqdnnh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gt2dvmsoelm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iuyudlql.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2odguykfx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2wapwiesq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2dackezhq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cczncmji.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gt2mbhcpnhx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gt2dzxsqcba.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gt2dqbsgwfg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2xtzbcutp.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gt2khilyqhu.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2recacyvf.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gt2bjbzggnr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gt2xzhuglom.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2sgohbcyq.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2cdsvtdyg.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2yzbpfdjd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gt2tdqkzjwi.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gt2ehremvtz.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvpxutzj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gt2zacynfkg.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjqyzwgs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2kbvyrruq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gt2yruhaegi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utmlygsk.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gt2vmlohquh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gt2vmnnsuow.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gt2jfikbgps.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2tcxruigk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gt2gnwajnxc.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gt2pycmocik.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gt2rcqjaksj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gt2anmtstde.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2xsokugka.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2mzuowdnk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2kpzgvkom.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2vccapveu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpqzgmyo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gt2gayukmmu.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gt2kckfynri.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipgexyza.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gt2ljvtivma.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gt2fjizliem.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gt2csaexmrp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gt2spnwrcyj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2osswtiao.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gt2twvszryq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gt2aajtcfho.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gt2xtjcahlp.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gt2cnbtjahk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gt2dujnippw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eghqaknx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrskwwvv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2rfsbskcz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gt2qnfepbgl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gt2xqbjelcb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2rcqkfnjx.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gt2knaxxnfb.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gt2vllblyww.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gt2gerpuqom.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gt2jrgxcups.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gt2xicdeghw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2tjuzcpoj.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gt2hppkmegq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gt2jbpketkr.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gt2rmqglstf.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvkruntl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2ikioywdj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2qephpymc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2vxhrvfct.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gt2dseqrdcd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cscttfuu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uprjptbj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2sbmvsedc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2sariuusj.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gt2ypyilnik.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gt2qqrdmhfy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gt2xtxsppbx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gt2olxwupgb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gt2oytckdua.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gt2cxizekvv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gt2gpbcirgr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gt2dbejgfkw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gt2iqrahddw.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hitnvlmi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmezzoc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gt2ukftjtmm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gt2ffiraoko.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2dfoacjfn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gt2ivswfjnm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gt2qqanzkyx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2ktfpjccu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gt2udohlvix.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpunmacx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gt2cfrfmomn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gt2yrmwthan.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gt2wyvegzow.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2tjhxfxjh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gt2tqripsda.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gt2uhbuvrul.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gt2jazakjtp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gt2ghuwdcaw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2fswtsooq.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gt2cykeitcc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2kvixdbmg.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gt2zabapajm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xlaasgny.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2jpipsfsm.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2vbankryv.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2xefatpdy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esbjeeet.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2pvxcfqzx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gt2oupzvdhn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2djontpfg.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytdupgeb.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ernxavya.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gt2etvdufeu.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2vqipbloy.html

TS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2mxhlpuny.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2oesnmrfy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gt2potizpcr.html

Ruby: JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2oprmuvpq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gt2vkjuipif.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixlccztc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgobqeti.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gt2oilhbpmr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2qgjeyxfc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gt2lokobhsv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2dasdswwo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gt2frvmfpeo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gt2iyhskprd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gt2okonlmqy.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gt2eqlunbfk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2jaotywky.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gt2cxqfdavk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2clbrmipa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2lgutjfag.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2xjlwmmbs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gt2qryggibw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gt2hmrzhisi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gt2dvvdvuzc.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gt2mtsqxwsh.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gt2fjdwxxrv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gt2fldxdmgl.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxweyvdc.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2boopipqn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gt2ljxeshar.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyxtgtoc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gt2sgpsnkeh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gt2vabgdaii.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gt2wgobrvyj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2erxaiqsr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gt2ezafhzmk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2rziblrkl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gt2lyhtojvn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gt2btenbibt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2kmjnsasy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2bnnpqfsc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2oopobnzq.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gt2nxerlcnh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2lhvdfgbt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmxzyacf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2soalywcx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2qxciuera.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2kfdecqlx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnqzz.top/Article/details/gt2azoyqexn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gt2mobjgltb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2yqhmygfs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gt2znwebrif.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2lektizko.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gt2jnoaxcga.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gt2oiagutvd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2wowznulv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gt2tafoxszo.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gt2zualxymy.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gt2cguhwbal.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2hgnqujex.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2xhgrrigl.html


<!-- 参考信息 -->