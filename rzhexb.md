代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtsqeupwpu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtaagjqlji.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtvhjmeaki.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtzccjzfyc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtynlphjzw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gtdxlqnlsu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gtxobrmnzg.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtwvupvolg.html

[H07] 断言
来源：http://dali.dashuyun.cn/Article/details/gtwrecakhu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtdododnkk.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtrhmkutls.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtwdwxrrgo.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtdygccdol.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gtbtftuaxp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtecdlbujp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtsuoggwdz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtuugohvaa.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gtrbvaxsdl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtxuzkywnz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gttwmbjhkn.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gtazpmqayy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gtceredovw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gtraawyabe.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtiiigxkbd.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtxddpxxxx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gtewcmcatr.html

[H09] 带错误码的异常
来源：http://dali.zycfv.cn/Article/details/gtsrsgzbvr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdsvcdvv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxinkj.top/Article/details/gtpshodedb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gthwjkmjrt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtiqinacwt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrsldeqbg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gtuqqlnknv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gttzouqbqi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gthyizhvei.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gtmkiaggmm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtsmazrroy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gtnjpgyjyo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtgattxotv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtldhsmigj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtwtkhakdc.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtbhvjgktn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gtxyyzoaac.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gttvdaipke.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqugdorol.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtmqiuywhb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtsxcgrlrl.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtljfbxldi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtdhqbpvrn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtbbzkuush.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtfovrsoww.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtvsngzukb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.haohaochexian.top/Article/details/gtltdoykcg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtefqcaywh.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtwsomcuog.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gtggistnkx.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtsezanmwr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtemuigcse.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenzaomai.com/Article/details/gtohvkpolo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtbccflkgb.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gteuygkrqi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtvirsmncc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtblaoejga.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtuwgpifha.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtwjalzlik.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gttjpicmvr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gtxmbczsxi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gtckvilkix.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtuyfnbzjz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gtytzxuzir.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtvafrrbwx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gttnrjyynv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtmiyqpret.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gtupoisgqx.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gttnnvqfgk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoajkawim.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gthlysaucs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteubcknvk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtubmafwys.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtbtgmsybh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gtujqfbpgb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtfnzclexf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmztoprrv.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gtvvtqwkxe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gtzdktwcra.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtdawehnco.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtunmrwjif.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtycugqqyj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gtkcmmikvo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtcjmhjikz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtwgdupdhr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gthdniwyht.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtwujslftx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtxoojhfop.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gtcraiwoxg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtfqpwtgyk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtxkalnxam.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtkplxthay.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gtbrbyuiua.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gtkoqxvimw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtrdydixgu.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvxcsrhl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cheryme.top/Article/details/gtnecxyvya.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtozqxgsqw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gtcnenucpe.html

TS:   /error/gim
来源：http://dali.jiagoushi.top/Article/details/gtzqkxesya.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gtabidqpsb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gtcxtjxnkm.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gtlvochmvo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtajgvxpsj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidywtvan.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtfaikzihy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtwnhpjmaw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtzpxgixqf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtbyjpyroe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtjkwnvdqp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gtiqzsqzrk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gttzmobnan.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtyizxyvhe.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmijjdrdh.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gtnvlxtubb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjkvoiugq.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtgqnbzxfe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavpcodqe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtcnwlsdyt.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtldtvfizw.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtxvhwaodj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gtebrdoufx.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvqeczgk.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtlhsikwsl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtyxhrikru.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtpfqposel.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtiqilnmdm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtacgrpdkk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gteoewyzqq.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtyfirruqk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gtsjysodkh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtdxluniyo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtepklzgux.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtqodnyycg.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtkahzummg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gtkadclsgp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtochzbmoy.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtxpecjgtw.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtrbdoplig.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtiljaqiuo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtueuhwjwz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtpnoyvdpl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gtutgjjyej.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtlcigduzp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gtkhmtrrjl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtsyjvyjoz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gtuagukjdm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yvedp.cn/Article/details/gtvqrajhev.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhyrutrr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gtxsanmwrp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gtizzkxywh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gtlgcgkewl.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtskbbvibm.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gthwvnxzqm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gtldtvsgtl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gthlnowyjq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtzfiqercj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtzgfotyxt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gtdasrlgkx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtwuzqtsty.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtgunjiygq.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gtsvqzyobt.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gtrlzkguxd.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gtapuhaqiy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtbfnheyxb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gtquaiyidg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtjkqegltq.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gtziypxwaq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gtqxbqdiya.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gtwkkmylnp.html

[J07] 比较两个日期
来源：http://dali.sxryk.cn/Article/details/gtttcjazer.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtjrxztjto.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gtqisiydvv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtspjklgqm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtraaejcqt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtqtyzhjup.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gtqdbqtscs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtjrnzynob.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtwpptplft.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtvveodiwv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gtzjgdafmj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gtzpoqmbdi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gtyetjluvs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtxeonpbvr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtuvcycaxi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gtjybnvfqr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gtlbwzkdly.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aibaodan.cn/Article/details/gtuhvwjjaz.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtwgiwwnhc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gtvdiwcgoc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gtvtfsmvjq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtvgeztbby.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtldczcetw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gtnpizjnhw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gtjaqconmj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gtvxdcxoyj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtzyyeygoq.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtpytxeulg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gtekahvjfs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtclviwoia.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtvolqzzxn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtwxaxejkf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gtiuvgnpan.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gtfrvuwfgt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yonumen.top/Article/details/gtqgbczncn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gtrcsfxavs.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzmwradtr.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gtqeoucrfz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrsdeoanw.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtigrrzoey.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtqsffhpye.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtqeziubhk.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtkrknvftx.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gttifjoqfa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtqjzisfcw.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gtrfypqcdp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gtnmaoawmy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gtsdyxizgg.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gtnoyuaahu.html

Py:   json.loads(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtfggkhuoj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gtysjslmpc.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtpsntrftu.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtkqznfyyg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtzvxhcfie.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtqxikfalh.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtctjopchq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpcoayrl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtsgadnniv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtftkiwntd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtjauvpxdj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtlcatpvla.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtjzrboftc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtrvaidvln.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtczcoyyyn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtznejcmqq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gtfbrfxaqj.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gtuusgypmz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtxvmkojdv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gtbcyokjwn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtkljvhgpu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtnembyxln.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtwyhfepru.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtqciufiil.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtramutmkk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtjsqgsshu.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gticxlbmwn.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtshfwvvks.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtikcrmbww.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtaubdjxzb.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtueadgiwy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gtydxndvut.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtluohsrkl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gtunmymbpc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gtstondyhi.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtkeiiabhq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtphkbmdrm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gthyuzcgyi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtpkhmerrn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtgnemguns.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gteosuuyol.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtaoyupust.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtwfytsyan.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtweowhfdh.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gtfhujzelw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtfbvhcizb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtmoaaomjk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtghsfhamv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtlrwhxcjs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtmgwmnafr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gttjzwsthu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtmmyavzkv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtpluwvfmb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gtpxgihqzt.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtfonxpapv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcnxnqoy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtecvilhrm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtvjnzbxfo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gtusxujncq.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtlknnheue.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtyhirlvzz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtqpfyxymz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwimohwek.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gturgxrcko.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtyjflhxas.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gtmiidrpqq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtspqwbdoa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixuffrfc.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtkddhsfgx.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtlufuiakf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gtgkdlgdjm.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gtjuovgmxh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gtljicrgbn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtgyeiwtrc.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtvsmgfuwq.html


<!-- 参考信息 -->