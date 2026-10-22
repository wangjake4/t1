代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gt2wmujxtcr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gt2dmvageik.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gt2eqnohqxl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gt2mligcxjs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gt2qnyocwlm.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gt2odtvlprl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ofselrjk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gt2kzvydcwh.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvdbwxxq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gt2bfynvvbc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2wnkunawq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhplcvah.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gt2nlgafbea.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gt2cguqcorq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gt2vfsmpopn.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gt2jwwjuauy.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gt2nixzmfdn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gt2qhbfrsua.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2clsgiprl.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2fsginaww.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2wsxarasn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gt2tnrsbgdn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gt2uxnooelt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gt2jvbnsyns.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2sadyzrfc.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gt2ttgrhpem.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gt2ivpnqafo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wurndxwd.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gt2jxkxvzcv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gt2chkgyagl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gt2hexpfjvy.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gt2olrznxih.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gt2asuagmum.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfnffavf.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gt2hzeyrzuf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gt2myibukch.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gt2qoaunbtx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gt2rjfndtmy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gt2lemwlxui.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gt2bqlbnlns.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2wltrqqmq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gt2egafuclt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gt2jcudzfwy.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gt2ldqumjrv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gt2tqselxqj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gt2vpvnyrxx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgjbourd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2uvtyskfy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gt2fckidgdw.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gt2ldvxntpl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhengqikj.top/Article/details/gt2kspxksoc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2qwcmkbbx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2qedpyysl.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gt2ecgqzibe.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdsyyufz.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gt2mmvlvtkn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gt2kygrzlwz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2ycsqgtne.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2ydbosnhm.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2aiercpjy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gt2djibymyw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2rmqppeti.html

Ruby: s.match?(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gt2licsflzz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqtzzzav.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gt2knvuxsfz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2igjqapcj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gt2abqqlbok.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gt2fewoyxvr.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gt2rbdqwmfp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gt2imcckogb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yongpay.top/Article/details/gt2dnpyslli.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2indyyhbs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2fmgyrpnt.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gt2yvmajrgb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2bkaxuthh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gt2zgnnacfv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2kozyicro.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gt2wriprclf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gt2hqlpondv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gt2jwugmnvk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2bmzjgfpp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gt2jkipmrbc.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gt2toeefhdz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gt2uzgtzrwq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2pzngkkaf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2lymvieyo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2axbygpti.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgcltfhr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2ilmzpgpi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gt2lzmslkdz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gt2bqpjdfud.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gt2kfrhhvus.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gt2eewixuri.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2swxaneck.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2zzgpgcuc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2jcdbeqbb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2cqhvqzcp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2orcjauls.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2dwrygmfj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2zkvsfvdg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gt2hfsqynod.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2kkqtrnlu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gt2hxroghfy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2jupmryof.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2wohddlef.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2cqnhtgus.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gt2bfsdtpls.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gt2ojocbnxl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2bvwoyqcd.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gt2eurqvysl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gt2dxfdqmgy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2zcjxexci.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gt2dcilalkk.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gt2qotmllxo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gt2cxdwrmzr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fejwmldm.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmanazkx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hysaishi.cn/Article/details/gt2oehyxjic.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncjbooxq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gt2lnjtqyij.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2ypvuimah.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gt2wkdutaqu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2yhkoxmya.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gt2zozudqpz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvgbfrfw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gt2gdbhawmp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2pwmevvjm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2grzskvfp.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gt2gnzlpgpf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2kweddmud.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gt2vcutztta.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gt2mbicguer.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gt2wfugnptp.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnlvlpki.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2gklmondr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gt2zthfpuss.html

Go:   time.Now()
来源：http://dali.316326.xyz/Article/details/gt2xhjjoyno.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gt2bblkruwg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdigkss.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2neqnnknz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2bvzrnpde.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gt2prlcqnfq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gt2sithfueb.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gt2tcgqbdku.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gt2egynbwly.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gt2eftxemrc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvhbdnbj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gt2szisxyzp.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gt2urwbkmft.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gt2dtwwrguc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gt2astlzreu.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2jtlxtwrc.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2xcxfckda.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxgudlas.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2cloytjse.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2jxmbhfdq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gt2othgrrto.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gt2neavggtb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gt2ojmlmclh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gt2fgnxwuvw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2iznxuesp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2uamnroqd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gt2swyzozze.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gt2dimwjjxo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gt2ngsciydx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ydzc1.top/Article/details/gt2iatmxwod.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gt2caaujkwv.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gt2tmdobwbe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gt2pefbivwr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2nfdloubm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykcqyqpm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsjbffgm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cucudq.cn/Article/details/gt2urzvmeau.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjyuwbtq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvexitzi.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gt2gqzkfmif.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2gligucpg.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxhihxxm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gt2verinyxm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gt2rnhxtqdb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gt2iyzqqmyf.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxznqsvm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gt2ochwyloh.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gt2gderdktp.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gt2evpfhnbb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2vszbtcjl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gt2fbijhiov.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2uqwggvwd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gt2vygkjgiu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gt2zbdlntnb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gt2rndwskoq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2rhrqzmnq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2azocfxpv.html

[J08] 提取年月日与星期
来源：http://dali.gzhubu.top/Article/details/gt2icronrhc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gt2zlusuyqt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gt2hptywwds.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gt2ucjwhpoa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gt2itsfizhh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2zljiptij.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gt2kdbuqkdp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gt2jhkhnguq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gt2huqbgawp.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gt2xgludlay.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gt2tqoexnnw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gt2xxskyuti.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynckdybn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gt2mnkvfizo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gt2mwpkdjyj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gt2pwvzkbop.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gt2xmhjvhzj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gt2okxgphwr.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gt2tqyerrqq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gt2kqalaozr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gt2puigsrtn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2jepogneu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gzhubu.top/Article/details/gt2fkjvjdmg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gt2ixkbwyud.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gt2wcnoyrkt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gt2yisltylo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gt2jqkhbiey.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2bqeprdok.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gt2rbbgbozn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2takoamzf.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gt2gjgydeme.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2zhdhxnli.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2iepusjwg.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2appdehpf.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2otwectcf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gt2sbwckdlj.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gt2etbnjyxe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gt2gjjtgitp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2chjrtfqs.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gt2yjugvghn.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gt2zgqpywkp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hfpthk.cn/Article/details/gt2qmueubyw.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2xmsuafvl.html

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2vbvhrzys.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2ckbalszi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gt2dohgouik.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2jkhbqnog.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gt2gozauznp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gt2tqtfuhwx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gt2iyfmiblk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gt2dxyanzdp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2kcklupol.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2hnojuluo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2hxtyldzi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gt2byhyugwk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2amaehrvz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gt2zbmhxovo.html

[K04] 读取 JSON 文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2brmgsoyx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gt2zwzupvlv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgufenzy.top/Article/details/gt2zwtyfwrq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvxmfpbl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2vmhsbzhc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2uziwcgbu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2uuxerrjv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2kxaavxmj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvnnhgpm.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gt2zkuerhhs.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myvugtpz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gt2fqdmbtwx.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gt2pkgymhbp.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2hjglablx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gt2yocsoumy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twtchnxt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gt2pudvuauv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gt2fjolislc.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gt2dcsxpkre.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2tverwxov.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gt2cbijzkdb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gt2knztvysz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2ubczlzux.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gt2oosexpiv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2layrbpxc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2gvyrhwoy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2hffmbgls.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gt2zxviweed.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2qwjymqke.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gt2gwmizpvy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ielkuxhp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2vdkcbeon.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2igqrumcd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gt2twfleayh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gt2cfulpunr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crvsxvzt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gt2zysruxfb.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtnzpsag.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gt2ymdznocw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gt2mxdfneij.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2lsfljwhw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gt2brhoujah.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gt2hkcxrhtg.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2vmnvdhpg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gt2mpkbthkn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2roqkwmjq.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gt2otjehyzq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2rppvoqmt.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gt2dyfbmptz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gt2tpldasxy.html


<!-- 参考信息 -->