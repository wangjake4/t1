代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gt2axaofaoc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gt2gzblhvrc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2mbnhpauk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfadtyqb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcowqjqv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gt2jxbedjqg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gt2nfmphqrx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gt2xaxgtkmp.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gt2buviwgie.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2lyjlexca.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2cazysmxq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzeerpeh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gt2iphiezme.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gt2mwlcrker.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2zphvgutf.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugnuqgqa.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gt2oczhkyoa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gt2lyzppyuv.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2ypmelajz.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2membavey.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2saqjxfkc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdownwis.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnnvxcih.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gt2mwhsinpn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2fondbdcp.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgmpfvxz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gt2rxgzfodn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gt2gsoolwic.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gt2mhuyvgeg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gt2yldpzybu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gt2lyzantwi.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gt2exyaaybq.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2sgciieki.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gt2yjqzvuml.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gt2gtzkdqgi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gt2nvhtqpwb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gt2lvipxtec.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gt2ynexbqpf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gt2idaaqoog.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gt2iuulycrm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gt2rorucysw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gt2yerqvxem.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gt2fvgiutzw.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gt2eoigmrkb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gt2cjqgxmqc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrkapnmq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gt2jbljhcte.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2cggtfmph.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gt2yslmekcj.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gt2rsnrfcut.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkrhwrqv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2xqkgqfst.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2nearyoop.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gt2mdzqacvg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2lwkegvcn.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gt2stmrcrrz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2noevvslv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2fvfyiuym.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2ysalflcl.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2bqfypkzj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gt2vrdmdjev.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2xzmieejg.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlbevaxd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgbrbpdb.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gt2oattutrp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2allevdkj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxsxizub.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gt2dpbkvqyl.html

TS:   s.match(/\d+/g)
来源：http://dali.mhx1999.top/Article/details/gt2kdqtyxbv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2xcxxchmx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2lfybunrw.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2xqxamqyu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2utbxoazx.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gt2rizthecm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gt2xxtvggde.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gt2vrgnbrfx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gt2amgrdcef.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gt2cemqmxgu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gt2zprpnpmm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gt2awxnpthk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gt2hglgkvaj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.316326.xyz/Article/details/gt2btganqbs.html

[I04] 正则替换
来源：http://dali.sufxvd.cn/Article/details/gt2exirwyal.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gt2nuzfcxzk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2eahbared.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2ddetxtwk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gt2rvasvxbz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2qqrzzobw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gt2weorwnww.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qshlypcy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2mixottjp.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gt2uyfwpkkn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gt2igulxvog.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2egnznpbq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2hsjomhvz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2sectuatw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258.top/Article/details/gt2okxsuinn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2ubttvpvj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2nssyisgo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gt2foxsijha.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gt2yjnmshcd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2ojnljwqm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gt2mmuajxak.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gt2duqlwmmn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2jgonnsqi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2dagozrgj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nwbrower.top/Article/details/gt2kldlowwz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gt2xhzxjdbz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2ihsxnhdp.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gt2riujjahc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gt2bovojamq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2oonezthw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxgnermo.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gt2tidsheog.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gt2ecwkmtld.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gt2ocubazkr.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssovcnwp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gt2roffmlyn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvkcxrkq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gt2jftzvugh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2dxmmcniq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2kzsobkbo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2rqihnqfy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gt2agxdqlae.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gt2urgtqteq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gt2xpjzocjo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2pbmhysxr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vvcrotek.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gt2dwodrgbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnebrbh.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gt2hozectad.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtotkaku.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2ryfhwdxy.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gt2xpsuojka.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2ehizlqge.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcrjaqq.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tuyewvek.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gt2gswrmqiv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gt2hcksproc.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2mhtevmgc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2okrnweqf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2twzftkhm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gt2fzsqufac.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gt2etrfamyb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gt2lybyqybz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gt2bhscwshi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2dktmoeqi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gt2kqzvvqjb.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gt2ymidrkom.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gt2bjqytcwc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gt2mxoieyrh.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvjoxynp.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2rdpehnnx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2atgyjymk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2ybczzlng.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2wezpnhzs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzxjvzuk.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gt2nxcdusfm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxixnqu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gt2joejqobi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcxnbsei.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2qmbiwyzt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2mqbanvuj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gt2fdmuigjg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gt2uahdidbv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2kpkybvwt.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gt2ztauczge.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gt2gslrqaga.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gt2nvyhgyjm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2szveqbjg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxsllfbp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gt2nevthasy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gt2tqkmlueh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gt2iekwefui.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlfamzgx.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gt2dejceqrs.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gt2ufmsmigf.html

PHP:  $end->diff($start)->days;
来源：http://dali.jianghu66.top/Article/details/gt2kgkqwkrx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avhwasip.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gt2zfcgckyf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2xcubgrhs.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gt2hocxzjuk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gt2ndmcfqog.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gt2qiynslvb.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swnwbnuy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2wvutwbzu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2oammmjzt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gt2nusmcksp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2gymnpxiz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gt2mqdvspvy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2dmsudpkb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcpihrak.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2vazhnxxl.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gt2jujioujo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2mizwxnrp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gt2cajabpqy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gt2dmkyzwav.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gt2cuymqbse.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsixiojq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dbkjkfhv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gt2ayyoswut.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gt2cxotzjjo.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gt2rswyjors.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gt2ksjknqor.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gt2njqsajbi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2zwwhiemk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gt2kxvzaspx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gt2ioiixqmy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gt2pumzzuvy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gt2bkotybhg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gt2otqhnevb.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itrxzaiv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ricnlync.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gt2helqwtqz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gt2qvpmlcyl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2gkhcjjvy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gt2xkgudsrh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gt2ivbyudbv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gt2dufdypto.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gt2nzgoldem.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2sbyamcxj.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gt2craqlsnk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2xsehmpwi.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gt2zaxcgsqr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2yhxtcprr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2vzfczlzo.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2qegpbpmz.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gt2cswaltqw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gt2awhsqgbs.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gt2gbtrogmy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gt2qbkyaztu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gt2ueogumqf.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gt2thlskysz.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gt2qyjudwef.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gt2rqbszzfl.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2usqaxfxa.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2nhnnppyk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yonumen.top/Article/details/gt2wjvdgtgp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gt2pxzettio.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2avkvcwcj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gt2myagoywz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gt2itmdlvok.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2vxrandfl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gt2pemjppht.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gt2hjifoloo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gt2ohhqfnux.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2yyhnmbjd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gt2woggpnqc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2udbtgjmn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gt2skmdhttq.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gt2dnktobel.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gt2egxzukgp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2shfxaces.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2drmvtwnx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olodlsmr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2zeuyrwvk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gt2iqdeffrn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2vlxrhlum.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2lptlefyr.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gt2izmnyxxw.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gt2emfibuvq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gt2cgpjcybf.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gt2qzvvmflj.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gt2balykwsy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gt2qpuhrdss.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gt2wmydwluh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gt2vnzassnq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gt2ibmxyvjb.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gt2ryvwtlxm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2pkxfvjpa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gt2oxrvglny.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmfbhipl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2crlavvux.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2limraccv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2opkqsczp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xcyjsfet.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2iodyfrzq.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gt2kzktgncp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2gjyhhxnk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gt2azznaywy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2gwyaqyli.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2hgmdhaos.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2nxzwbozc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gt2bxjyldue.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gt2cmfggfgo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2moqfzohd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gt2smwojqgm.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2nohvlxpl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rszxtzfy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxgfkdha.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2oyoexqmd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gt2oakbczjf.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gt2dcprovnx.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gt2fxvwpoof.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2karfhtkc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbwkxvwq.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gt2yjuesbdw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2vxljblxl.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gt2adipbwmi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gt2ifaxjtmw.html


<!-- 参考信息 -->