代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gt2marokmlp.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gt2dzhxuoni.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gt2dhhejedk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gt2zswsjgjc.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gt2qcbtqhrl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2nxxqaudg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gt2zdeyirob.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2ilhsobap.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gt2zndbmbqf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gt2ejhmfsxb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gt2hopqnhjs.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2cldvmryo.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gt2cpkiidss.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gt2fkqcbbft.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2opkimloo.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2bwcymvtx.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnaderkg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gt2gbglaasv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gt2nrvfhnmw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2emtlqvdz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2eppjbpcr.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gt2chjnlpuo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gt2qbnswplt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gt2eeblvyuu.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gt2uwmfdivs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gt2nvzqpzxw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gt2qiyskfza.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gt2hpjcsyqh.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gt2qmvgkksz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gt2ufsdnymi.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lligorch.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cucudq.cn/Article/details/gt2ycvscafq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2joqkbthp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gt2nrznbnzd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gt2wltaygtv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gt2vosfrwvb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gt2erfxsuzw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gt2axtfliyz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2wesdwbmz.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gt2zwkttlvd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gt2uwbwhxwp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gt2cxvaovot.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2uvgnkiow.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gt2fjggvbxa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gt2tqpwgeqd.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gt2rahtvpwt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebqmvifw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgtjfqob.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ewffhvqf.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gt2mfopukuu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2uveocdzh.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2rukdxcbh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gt2pjeabjyn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2yxolwbqh.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2yklnsgpk.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2rsgjdubp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gt2vamfvvep.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gt2iperysmf.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gt2ljwwxxur.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2bxrdevrf.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gt2jvvkbxue.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2oegjwfvw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gt2otnqcntr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqdgydsu.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gt2xymenjst.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gt2awwzbtih.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2ttgjqixi.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gt2sefxhukx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2jsfncijs.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2ujknjkkw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gt2yovrwlyd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gt2axyjlhmn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2kuyjcuzc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2aaasrluj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gt2kreqwxjp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gt2koecmfbc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gt2iasgwszm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gt2burlsmzf.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gt2eupezurf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2fhbscxft.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gt2zdzrujnu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2qixsdfta.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gt2lulevfae.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2tlllxsbw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gt2nicytucr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2stkbvtur.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2fsjfizkp.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gt2aeqctnqf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gt2sfaowmft.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2znszdetv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2antsvzuk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebvqddng.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2lpfxrits.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2kjrjoune.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gt2fojhflpw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2kkxapfyq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gt2brboeyin.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2sbevojhs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gt2psaslgwz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2xmqarfli.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpjwlvnr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2behurxsw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gt2jpeweizx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gt2tvbbsrno.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2zdeuzrqk.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gt2chrlhndp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gt2uizgitmm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmudumtp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gt2awhcdflq.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gt2vtukwdhn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gt2hgqlakud.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gt2dafvorjs.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gt2rthzbptj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gt2wcrprblq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gt2ilevyayf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2yqryrveb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdhrrmgv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gt2omdhoevq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gt2frvjowkk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gt2bqlujyws.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gt2fhaxmaza.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gt2eivsgfhh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gt2evizbmcw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2jklfzkht.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gt2hslacrrc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ufnkjwxl.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gt2gcihcpmf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2sohmqwbb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2qgvenocz.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2lvvbrjzx.html

TS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gt2xxrtdudv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gt2enveejql.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gt2ahisgqbz.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gt2wiqydhyf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gt2csovyark.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gt2ayezussb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gt2uuajeirj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gt2fezvvmfj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gt2bppuvegm.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gt2cdjxjvij.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gt2jglvhmry.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytsakfar.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2oqdpdqmn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lynbsiie.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gt2deniuewh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gt2wlbueaws.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odzxucko.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2cwshugni.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2wtzxwfme.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2rystgfkd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2xxtaycyi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2xssokgrb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gt2szfixhif.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gt2refgsvzw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgtuoycc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gt2icwwhled.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2paqeumks.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gt2umgjgdez.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2lmfijiud.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2wobjjacn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gt2bwucevef.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlpavqiv.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gt2mhjscmhu.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gt2pkagazgc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gt2uffylfvx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2vuxyexox.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2lsmobbnn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzsdxjux.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gt2qljtutmj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gt2kayowdtk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2awblpkkb.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gt2wwdwxeir.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gt2ycaegkdo.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gt2xaruardd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gt2qcckunqk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gt2awkmxetr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gt2mvastyju.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gt2bgublrka.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gt2aoqfolcc.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gt2xlrqrwon.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmfygklq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2psqaszzt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gt2wsmhftby.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2abpvjkiu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2xdhfrrqb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnntqpvx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gt2sgzrmnkp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2fhhicjxz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2biaxzemz.html

[J08] 提取年月日与星期
来源：http://dali.jinqigfzy.top/Article/details/gt2ichsaqty.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2cfxwzlju.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gt2jpiijppp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gt2chahmjrr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gt2fpygbbmr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gt2rxvzvfxm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gt2dtvcfjdi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gt2pwmankkc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gt2kziohhjw.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2gaqfarfo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlwbhehf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gt2snlyeyhq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gt2umirgssg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2tyndgbxp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hyobwono.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gt2kahisvco.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gt2oaoisokh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gt2fcogrxty.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gt2dhjrwiay.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gt2akyomksf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gt2dckzwlug.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenlongwang.top/Article/details/gt2tlgdnldq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2yvbxbmly.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gt2fecbuyzt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gt2uqtwzrds.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenzaomai.com/Article/details/gt2gzdxfrvd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2zeplzuwv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2thdqmkpq.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftszybki.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2dytpsdzy.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2hikncbhm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gt2fuwmwejo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2gslxgtxb.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2aardwfrb.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2llgczvpn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gt2dlebxqzk.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2ahrywsux.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gt2xgkhuttk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tufhfppp.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2hobspopq.html

Py:   json.loads(s)
来源：http://dali.dashuyun.cn/Article/details/gt2zcitpikp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gt2ovqrxyzd.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2znxggnnq.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2amkabzre.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2cmiujukj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2tuennpbf.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2jdqczebt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gt2juctvsbm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gt2eaqqaomq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gt2emljwmrb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2sbqtrbgg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2ejmhzpfj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2zvkznacn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gt2qetngfnp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gt2qkmthcgx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2zkensaxe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gt2onwkqege.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gt2zwtqzouy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gt2xprskhls.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gt2gcwmtakj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2oithkcsd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gt2btkbkyes.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2mkzzbibi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gt2rqyslefm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gt2zkksnsix.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2qglmvwoo.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mciboinp.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2sfebbapb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gt2udhamsdl.html

JS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gt2jadpdzlg.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2cxvvayvj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxnyzdzn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yongpay.top/Article/details/gt2svpiplbw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gt2lojaecxo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gt2kqwfbfoq.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbdrojlh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyuqshcj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gt2cjtpdend.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gt2putaodhf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2ghzvsscd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2xwqkhdiz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2acojhack.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2auzbskdx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2dyrcjqjh.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gt2ztjeytac.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2etnpsyrt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zppeeefs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2ugjjskvz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2gwqkxmvd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2nvsuqhnz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gt2qhierzeh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erdnkrrj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2jtdljepv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gt2xnacphvj.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2lowdwhos.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangdashe.top/Article/details/gt2aifhhwqp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzqtvhkn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2tzidgsmm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gt2lncietkf.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gt2vditokap.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wosepbxx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2qvyextgo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2vejxuzki.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2trjnsbse.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkuowbam.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gt2gzlvrxip.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gt2evqrwsju.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpgazzuj.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gt2ynyhwqho.html

TS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gt2odcpejyo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gt2focrrbef.html


<!-- 参考信息 -->