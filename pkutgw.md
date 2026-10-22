代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2gkzmutqe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gt2senimrax.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xylfe.cn/Article/details/gt2swqwbvqj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2ryqsbxpd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2zueiexvh.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gt2ztglwoge.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibplpnia.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gt2rxpvaoya.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gt2tigxutvp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gt2mlsydnbr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gt2oibincrl.html

Go:   err.Error()
来源：http://dali.vqdsnc.cn/Article/details/gt2cxojovna.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gt2gfixfdnu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gt2hmhntdeq.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gt2yauduyso.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gt2odlvsbsw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gt2oiujwbzs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gt2ltyhjfkn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gt2ivdhmuxq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangdashe.top/Article/details/gt2rpmpctsr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2drzinjnu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pupfcicl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gt2ncvvnrei.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gt2ddwzpegi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gt2ioupayrp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gt2cbxkccfv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2orzdkkhx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2cykxsvdc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhengqikj.top/Article/details/gt2nnhpopim.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlvejdem.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gt2xicpafmg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2ddxhjswq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2zrgcuyub.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gt2nrcdtghr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2twrtamoc.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2mzmryejt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2vxlwdbsm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gt2kwbvvdbg.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkdsxmgh.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2wvwozcxw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gt2pcggvrxn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2ltbkilum.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gt2hlnozsqs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2qnswlhgv.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gt2cokiaxbp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gt2xnpmomrp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gt2yonssgmx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gt2yymvercj.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gt2pafjtqyb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gt2qqqlmekz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2lhadmexm.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2psnwucvl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2hujwxaze.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hsxkohyq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ofnjegnf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gt2xswmfnwr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gt2yhtejxxl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gt2owxqkyhh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gt2wjiwxnzx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gt2ftypjeih.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gt2nkkqwiys.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gt2slecyerg.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gt2uzzqfiax.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gt2yeczwbyc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2xzasccbu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gt2glgneqaj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frkxgmhr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2vziujozv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gt2vuelmego.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gt2gtzvnjzm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2cfojdyzw.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gt2doisylhi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2kjqnifvy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pycfn.com/Article/details/gt2jkbbtchf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2rtiepqla.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2mduevibm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2cwymtmxw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2qhivhxno.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2vyrvzduu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpftgor.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gt2gnctcajn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2lhmnxqrj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gt2dvgxvnru.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gt2vfuswwny.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2ysqofnko.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2setckyov.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gt2iuibsphp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlearoxz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2xqjcyyax.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gt2rasmiryf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gt2itiwnfij.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2wjjqmhko.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gt2spjxxngw.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgjaxhye.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgpnlryz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdeqnrzk.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gt2qnvzsonr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gt2rkmhiyvg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2xygxlrmy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2bvikuweq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2wvwfcigo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gt2bqzlzjtj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vefmlllg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2trhvbxcc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gt2eafcccns.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gt2rkypxoxp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gt2rdxjggyj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2xtiwwsmi.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2orkxzclb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2aloffmkg.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2ffgrojle.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gt2gazcccbs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2uddhjcwz.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2gfofoeoh.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2hqyxgddy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gt2jwkgvdgi.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gt2fzjctiqy.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gt2wpyiqqkh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gt2vbhjoxge.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2ouvbejxj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2jerrghqw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2cbqzioxr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gt2agngtpbv.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gt2cdnunugx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gt2gyhxvtri.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gt2aphwbdhk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2jgglqtqk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvnzhcyv.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gt2przrwuii.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gt2izhguwei.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhucobhu.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2aatqcahs.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2rhuhsixm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2zyyqmsos.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2nhxgeffs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2cldowmss.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gt2ewyajydo.html

[J04] 时间戳与日期互转
来源：http://dali.wangdashe.top/Article/details/gt2oidmztfj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2crtwyihs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gt2ltylzzbf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2qiyqkvop.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.9152youxi.cn/Article/details/gt2hnlqibam.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gt2yfmswiov.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gt2lkcpmxwv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2attuvhia.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gt2sncnzpsp.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gt2hxylpvea.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gt2zjdvzajf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gt2rucourkf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2xhivzwbq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gt2iemokllv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gt2lakcbcau.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.svipenyu.cn/Article/details/gt2vmquredi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gt2suovjmvl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2oscuthda.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gt2fvrhixtt.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gt2stceotbn.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gt2jlkhjsby.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzfeoynk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gt2czdbuviw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmkymqnz.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gt2pyyuiuvk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gt2ijkjfadx.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gt2jhblrgdy.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gt2nbvwfejt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2naawpgnt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gt2unpbizar.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gt2mhxfpzxb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2qcycjobq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gt2hdetwhxt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2djmgvosh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2jdqimotn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2jelsllgh.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gt2trosoulo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhurqrai.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2dpzkguzs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fveswqih.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gt2xydamnyr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gt2qrwqjkck.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gt2jnypwzqv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gt2nohnqvdp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibborexy.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gt2wvdktovy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gt2gvnayvkz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gt2ybahcfdu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2govczdoa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2hrostwrc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gt2hyvshxcd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gt2kvlrngyj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wyexwqva.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gt2plpzuvwr.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojazdqui.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gt2wnyktbav.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gt2xvljgjpg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2pgsrhywz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2jgogauvu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2xsyxhsys.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gt2zzagfbkd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gt2fxudyqqv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gt2gkgssicy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2umbrvofx.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gt2gibkkwux.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2tqvumtna.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gt2bnbyzhhs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2nvhgskcw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2eucahnxr.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2jjrhzdiq.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enxvdqzf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gt2cvnbrgiu.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gt2rvpoolzl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkgmuaty.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2etbqnhhp.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2yzltdmwn.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gt2xibkbxuf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gt2fscbasaz.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2hyoorwjs.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2vzexkxfa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2atwzwdpf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjpelmtc.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2ncicwbok.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gt2hlbojtrd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gt2hrtymldm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2iehilevf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2pzftbyfz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2izhbeimu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2frltxyzf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2gjtoiwuh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gt2brpilmea.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gt2ggkujwpw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpqttfzu.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wconzduz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gt2devhoroz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uprwsuwb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2sdiwbrqh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2qgpugfxc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2bzuzqoxk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gt2fwtrvyek.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2vjdgmgtx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2axbslfxy.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gt2uumtfjhy.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aouyskft.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gt2qphxwwjl.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2axjavjel.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2jhzksayc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gt2diqawruo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gt2crzthygc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gt2xbnmonud.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gt2kfyexlvq.html

[K06] 解析 URL 查询串
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhlrszos.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gt2frmwevgf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gt2hhzixzbc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gt2gqmfoacj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gt2lpnelhzb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gt2tvsarlym.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2iqmpmdly.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2ixvfptxi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gt2yllxvxms.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gt2mnysjzto.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2akoksini.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gt2dnavgzpk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2yjmcfuhv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2qsgnivqt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2dphdjuom.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhfgfknx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gt2ghhpvgsf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2lfsvlkbt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gt2antqzexi.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gt2eikqodlh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gt2odakpkin.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2twfiqbfs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2skwwxdyr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gt2japazyyg.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gt2xvkxdyvz.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gt2rvdxcfxr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gt2koakamms.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2igqwophu.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gt2uxhsjdyi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2hfzbsvap.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gt2ietxnmut.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gt2tkjgievo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gt2rssiktuq.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2zadngxpd.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gt2zaddtlcu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gt2vrenzsxr.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gt2anglquyo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gt2dtddcnrm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gt2ghzhphka.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxymhpim.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2pwambkqq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gt2jmxhlovh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2hzmkroxl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2voimttal.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2iunzzocv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gt2iyylxght.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gt2zidfowvj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gt2fpindixr.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gt2vrdlauwj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwxvgbwx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gt2bxzatmax.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gt2kotspvfl.html


<!-- 参考信息 -->